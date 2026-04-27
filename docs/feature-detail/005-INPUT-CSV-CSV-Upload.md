# INPUT-CSV: Upload CSV/Excel

## API Basic Information

| Item | Content |
|------|---------|
| Unique ID | INP-UPLOAD |
| API Name | Upload CSV/Excel |
| Type | POST |
| Endpoint | /api/data/upload |
| Category | Data Input & Intelligence |
| Status | Planned |

---

## Summary

Upload spreadsheet for bulk emission data. CSV file upload functionality for bulk data import.

---

## Supported Data Types

| Data Type | Description |
|-----------|-------------|
| Order Data | Purchase orders from DOG/ORDIA |
| Shipment Data | Logistics and transport data |
| Product Data | Product information and quantities |
| Activity Data | Energy consumption, fuel usage |

---

## Workflow

```
CSV File Upload → Parse & Validate Columns → Create Orders → 
Create Shipments → Match Emission Factors → Calculate CO2e
```

---

## CSV Format Requirements

| Column | Required | Description |
|--------|----------|-------------|
| orderId | Yes | Unique order identifier |
| productId | Yes | Product/SKU identifier |
| quantity | Yes | Product quantity |
| unit | Yes | Unit of measurement |
| amount | No | Purchase value (¥) |
| transportMode | No | Shipping method |
| distance | No | Transport distance (km) |

---

## Implementation Notes

- Supports customizable column mapping
- Data validation during upload
- Automatic processing of multiple records
- Essential for companies with existing spreadsheet data

---

## Related Features

- INPUT-EXCEL (Excel Upload)
- INPUT-BULK (Bulk Data Import)
- DATA-VALIDATE (Data Validation)