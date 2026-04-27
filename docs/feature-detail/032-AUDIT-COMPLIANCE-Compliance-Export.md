# AUDIT-COMPLIANCE: Compliance Export

## API Basic Information

| Item | Content |
|------|---------|
| Unique ID | AUDIT-COMPLIANCE |
| API Name | Compliance Export |
| Type | GET |
| Endpoint | /api/reports/compliance |
| Category | Reporting, Dashboard & Audit |
| Status | Planned |

---

## summary

Export data in compliance-ready formats. Supports GHG Protocol, EU CBAM, Japan SSBJ.

---

## Supported Standards

| Standard | Region | Description |
|----------|--------|-------------|
| GHG Protocol | Global | Corporate standard |
| EU CBAM | EU | Carbon border adjustment |
| Japan SSBJ | Japan | Sustainability reporting |
| ISO 14064 | Global | GHG accounting |
| TCFD | Global | Climate disclosures |

---

## Export Formats

| Format | Use Case |
|--------|----------|
| PDF | Formal submissions |
| Excel | Detailed data |
| JSON | API integration |
| XML | Regulatory filing |

---

## Compliance Templates

| Template | Fields Included |
|----------|-----------------|
| Corporate Standard | All scopes, categories |
| CBAM Report | Scope 3, transport |
| SSBJ Disclosure | Japan-specific |
| CDP Response | Annual disclosure |

---

## Validation

| Check | Description |
|-------|-------------|
| Completeness | All required fields |
| Accuracy | Data consistency |
| Format | Standard compliance |
| Certification | Third-party ready |

---

## API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| /api/compliance/export | GET | Export compliance report |
| /api/compliance/templates | GET | List templates |
| /api/compliance/validate | POST | Validate data |

---

## Implementation Notes

- Multi-framework support
- Pre-built templates
- Audit-ready exports

---

## Related Features

- REPORT-EXPORT (PDF/Excel Export)
- AUDIT-TRAIL (Data Audit Trail)