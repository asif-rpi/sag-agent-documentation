# CALC-MASS: Mass-based Calculation

## Feature Basic Information

| Item | Content |
|------|---------|
| Unique ID | CALC-MASS |
| Feature Name | Mass-based Calculation |
| Category | Core Carbon Calculation Engine |
| Priority | Critical |
| Implementation Phase | MVP (Phase 2) |

---

## Purpose

Calculate carbon emissions using a mass-based approach where emissions are determined by multiplying product quantity by the corresponding emission factor (EF).

**Formula:**
```
CO2e = Activity Data × Emission Factor × GWP
```

- **Activity Data** = Quantitative measure (liters fuel, kWh electricity, km traveled, kg material)
- **Emission Factor** = Conversion coefficient (kg CO2 per unit)
- **GWP** = Global Warming Potential (non-CO2 gas ke CO2 equivalent-e convert kore)

---

## Supported Calculation Methods (GHG Protocol)

| Method | Accuracy | Data Required | When Used |
|--------|----------|---------------|-----------|
| Supplier-Specific | Highest | Actual supplier emissions | Supplier provides primary data |
| Hybrid | High | Mix of supplier + secondary | Transitioning to actuals |
| Average-Data | Medium | Industry-average factors | Supplier data unavailable |
| Spend-Based | Lowest | Financial spend only | Starting point / quickest |

---

## Request Specification

### Headers

| Header Name | Required | Value |
|-------------|----------|-------|
| Content-Type | Yes | application/json |
| Authorization | Yes | Bearer {JWT token} |

### Request Body

| Parameter | Type | Required | Description |
|-----------|------|----------|-------------|
| productId | string | Yes | Product identifier |
| quantity | number | Yes | Product quantity (must be > 0) |
| unit | string | Yes | Unit of measurement (kg, ton, g, etc.) |
| efId | string | Yes | Emission factor ID |

### Request Example

```json
{
  "productId": "prod_xyz789",
  "quantity": 100,
  "unit": "kg",
  "efId": "ef_coal_001"
}
```

---

## Related Features

- CALC-SPEND (Spend-based Calculation)
- CALC-DUAL (Dual Mode Calculation)
- CALC-UNIT (Unit Conversion)
- EF-DEFAULT (Default EF Database)

## Response Specification

### Success (200 OK)

| Field | Type | Description |
|-------|------|-------------|
| calculationId | string | Unique calculation ID |
| productId | string | Product ID |
| quantity | number | Input quantity |
| unit | string | Unit of measurement |
| efValue | number | Emission factor value |
| efUnit | string | EF unit (e.g., kg CO₂/kg) |
| emissions | number | Calculated CO₂ emissions (in kg CO₂) |
| timestamp | string | Calculation timestamp (ISO 8601) |

### Response Example

```json
{
  "calculationId": "calc_abc123",
  "productId": "prod_xyz789",
  "quantity": 100,
  "unit": "kg",
  "efValue": 2.5,
  "efUnit": "kg CO₂/kg",
  "emissions": 250,
  "timestamp": "2026-04-27T10:30:00Z"
}
```

---

## Error Responses

| HTTP Status | Error Code | Description |
|-------------|------------|-------------|
| 400 | INVALID_INPUT | Missing or invalid parameters |
| 401 | UNAUTHORIZED | Missing or invalid token |
| 404 | NOT_FOUND | Product or EF not found |
| 500 | INTERNAL_ERROR | Internal server error |

### Error Response Example

```json
{
  "error": "INVALID_INPUT",
  "message": "Quantity must be greater than 0"
}
```

---

## Usage Examples

### curl Example

```bash
curl -X POST "/api/calculate/mass" \
  -H "Content-Type: application/json" \
  -H "Authorization: Bearer eyJhbGciOiJIUzI1NiIs..." \
  -d '{
    "productId": "prod_xyz789",
    "quantity": 100,
    "unit": "kg",
    "efId": "ef_coal_001"
  }'
```

### Frontend (React) Example

```typescript
const mutation = useMutation({
  mutationFn: (data) => apiRequest("/api/calculate/mass", "POST", data),
  onSuccess: (result) => {
    console.log("Emissions:", result.emissions, "kg CO₂");
  },
});
```

---

## Related Features

- [CALC-SPEND](./002-CALC-SPEND-Spend-based-Calculation.md) - Spend-based Calculation
- [CALC-UNIT](./004-CALC-UNIT-Unit-Conversion.md) - Unit Conversion
- [EF-DEFAULT](./013-EF-DEFAULT-Default-EF-Database.md) - Default EF Database