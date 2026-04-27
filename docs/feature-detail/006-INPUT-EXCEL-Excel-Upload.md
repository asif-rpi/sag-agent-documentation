# INPUT-EXCEL: Excel Upload

## API Basic Information

| Item | Content |
|------|---------|
| Unique ID | INPUT-EXCEL |
| API Name | Excel Upload |
| Type | POST |
| Endpoint | /api/data/upload |
| Category | Data Input & Intelligence |
| Status | Planned |

---

## Summary

Upload Excel spreadsheet for bulk emission data. Excel file upload capability for importing structured data.

---

## Supported Formats

| Format | Extension | Support |
|--------|-----------|---------|
| Excel Workbook | .xlsx | Full |
| Excel 97-2003 | .xls | Full |
| CSV (via Excel) | .csv | Full |

---

## Features

- **Multiple Worksheets**: Process data from multiple tabs in a single file
- **Column Mapping**: Map Excel columns to system fields
- **Data Validation**: Validate data integrity during upload
- **Formula Support**: Handle calculated fields in Excel
- **Merged Cells**: Process merged cell content correctly

---

## Excel Structure Example

| Sheet Name | Content |
|------------|---------|
| Orders | Order details and quantities |
| Products | Product information |
| Transport | Shipping and logistics data |
| Summary | Aggregated data |

---

## Implementation Notes

- Maintains formatting and structure
- Provides error reports for issues found
- Supports complex Excel structures

---

## Related Features

- INPUT-CSV (CSV Upload)
- INPUT-BULK (Bulk Data Import)
- DATA-CLEAN (Auto Data Cleaning)