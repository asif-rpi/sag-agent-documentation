# REPORT-MULTI-FRAMEWORK: Multi-Framework Report Templates

## Feature Basic Information

| Item | Content |
|------|---------|
| Unique ID | REPORT-MULTI-FRAMEWORK |
| Feature Name | Multi-Framework Report Templates |
| Category | Carbon Passport & Document Generation |
| Priority | Critical |
| Implementation Phase | Phase 3 |

---

## Purpose

Ek-i data theke multiple compliance frameworks-er jonno formatted reports generate korbe simultaneously.

---

## Supported Frameworks

| Framework | Description | Region |
|-----------|-------------|--------|
| EU CBAM | Carbon Border Adjustment Mechanism | EU |
| Japan SSBJ | Sustainability Standards Board | Japan |
| ISO 14064 | Corporate GHG inventory | Global |
| ISO 14067 | Product carbon footprint | Global |
| GHG Protocol | Scope 1, 2, 3 | Global |
| CSRD | Corporate Sustainability Reporting | EU (Future) |
| TCFD | Climate Financial Disclosures | Global (Future) |

---

## Report Generation

| Framework | Output Format |
|-----------|----------------|
| EU CBAM | PDF + Excel |
| Japan SSBJ | PDF + XML |
| ISO 14064 | PDF + JSON |
| GHG Protocol | PDF + Excel |

---

## Features

| Feature | Description |
|---------|-------------|
| Single Source | One data, multiple reports |
| Auto-mapping | Framework-specific fields |
| Validation | Compliance checks |
| Scheduling | Automated generation |

---

## Implementation Notes

- Simultaneous multi-format export
- Framework-specific validation
- Reduce duplicate work

---

## Related Features

- REPORT-PASSPORT (Carbon Passport PDF Generator)
- AUDIT-COMPLIANCE (Compliance Export)
- REPORT-EXPORT (PDF/Excel Export)