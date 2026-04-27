# INPUT-MANUAL: Manual Entry

## API Basic Information

| Item | Content |
|------|---------|
| Unique ID | INP-MANUAL |
| API Name | Manual Entry |
| Type | POST |
| Endpoint | /api/data/entry |
| Category | Data Input & Intelligence |
| Status | Planned |

---

## Summary

Submit a single transaction/emission record. Manual data entry forms for inputting carbon emission data.

---

## Form Types

| Form | Description |
|------|-------------|
| Order Entry | Single order data entry |
| Shipment Entry | Transport/shipping data |
| Product Entry | Product and emission factor |
| Activity Entry | Energy/fuel consumption |

---

## Form Fields

### Order Entry Form

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| productId | string | Yes | Product identifier |
| quantity | number | Yes | Product quantity |
| unit | string | Yes | Unit (kg, ton, etc.) |
| amount | number | No | Purchase value |
| supplier | string | No | Supplier name |
| category | string | No | GHG Protocol category |

---

## Features

- **Validation**: Real-time data validation
- **Auto-save**: Prevent data loss
- **Guided Input**: Field suggestions and help
- **Quick Entry**: Keyboard shortcuts for efficiency

---

## Implementation Notes

- User-friendly web forms
- Supports small datasets
- For data from non-automated sources

---

## Related Features

- INPUT-CSV (CSV Upload)
- INPUT-EXCEL (Excel Upload)
- DATA-VALIDATE (Data Validation)