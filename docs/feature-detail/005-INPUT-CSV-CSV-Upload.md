# INPUT-CSV: CSV Upload

## Feature Basic Information

| Item | Content |
|------|---------|
| Unique ID | INPUT-CSV |
| Feature Name | CSV Upload |
| Category | Data Ingestion & Integration |
| Priority | Critical |
| Implementation Phase | MVP (Phase 1) |

---

## Purpose

CSV file upload functionality for bulk data import and processing of carbon emission data. This is the primary data input method for the SAGGreen Agent system.

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