# REPORT-EXPORT: Export Report

## API Basic Information

| Item | Content |
|------|---------|
| Unique ID | REP-EXPORT |
| API Name | Export Report |
| Type | GET |
| Endpoint | /api/reports/export |
| Category | Reporting, Dashboard & Audit |
| Status | Planned |

---

## Summary

Export dashboards as PDF or Excel (GHG format). Export emission reports in PDF or Excel format.

---

## Export Formats

| Format | Use Case |
|--------|----------|
| PDF | Formal reports, submissions |
| Excel | Further analysis, sharing |
| CSV | Data processing, imports |
| JSON | API integration |

---

## Export Options

| Option | Description |
|--------|-------------|
| Full Report | Complete emission report |
| Summary | Executive summary only |
| Scope-specific | Scope 1, 2, or 3 only |
| Category-specific | Single category |
| Custom Date | Date range selection |

---

## PDF Features

| Feature | Description |
|---------|-------------|
| Branding | Company logo, colors |
| Charts | Embedded visualizations |
| Tables | Formatted data tables |
| Headers | Report metadata |
| Footers | Page numbers, date |

---

## Excel Features

| Feature | Description |
|---------|-------------|
| Multiple Sheets | Each scope/category |
| Formulas | Calculated fields |
| Charts | Embedded charts |
| Formatting | Professional styling |
| Raw Data | Underlying data tab |

---

## API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| /api/reports/export | POST | Generate export |
| /api/reports/export/pdf | GET | PDF format |
| /api/reports/export/excel | GET | Excel format |

---

## Implementation Notes

- Professional report templates
- Automated generation
- Scheduled exports

---

## Related Features

- REPORT-TOTAL (Total CO₂ Emission Report)
- AUDIT-COMPLIANCE (Compliance Export)