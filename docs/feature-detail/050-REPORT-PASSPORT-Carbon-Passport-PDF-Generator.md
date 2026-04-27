# REPORT-PASSPORT: Carbon Passport PDF Generator

## Feature Basic Information

| Item | Content |
|------|---------|
| Unique ID | REPORT-PASSPORT |
| Feature Name | Carbon Passport PDF Generator |
| Category | Carbon Passport & Document Generation |
| Priority | Critical |
| Implementation Phase | Phase 3 |

---

## Purpose

Audit-ready PDF document generate korbe per shipment ba per period, EU CBAM, SSBJ, ar ISO 14064 format-e.

---

## Document Contents

| Section | Description |
|----------|-------------|
| Company Information | Name, address, industry |
| Reporting Period | Period & base year |
| Organizational Boundaries | Scope of reporting |
| Scope 1, 2, 3 Emissions | Per-category breakdown |
| Total Emissions | Year-over-year comparison |
| Methodology | Methods used per category |
| Data Sources | Quality indicators |
| Emission Factors | Database references |
| Exclusions | Justification |
| Assumptions | Made assumptions |
| Reduction Targets | Future targets |
| Verification Status | Verification info |

---

## Compliance Formats

| Format | Description |
|--------|-------------|
| EU CBAM | Carbon Border Adjustment |
| Japan SSBJ | Sustainability Standards |
| ISO 14064 | Corporate GHG inventory |
| ISO 14067 | Product carbon footprint |

---

## Generation Flow

```
Data Collection → Carbon Calculation → Compliance Formatting 
→ PDF Generation → Verification Readiness
```

---

## Technology

| Component | Technology |
|-----------|------------|
| PDF Generation | Puppeteer / WeasyPrint |
| Templating | Handlebars |
| Styling | CSS/HTML |

---

## Implementation Notes

- Full traceability
- Audit-ready documents
- Multi-format support

---

## Related Features

- REPORT-EXPORT (PDF/Excel Export)
- AUDIT-COMPLIANCE (Compliance Export)
- AUDIT-TRAIL (Data Audit Trail)