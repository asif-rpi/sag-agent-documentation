# INPUT-MANUAL: Manual Form Entry

## Feature Basic Information

| Item | Content |
|------|---------|
| Unique ID | INPUT-MANUAL |
| Feature Name | Manual Form Entry |
| Category | Data Ingestion & Integration |
| Priority | High |
| Implementation Phase | Phase 2 |

---

## Purpose

Manual data entry forms for inputting carbon emission data when automated sources are unavailable. Supports companies in early stages of carbon accounting.

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