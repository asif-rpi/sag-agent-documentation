# REPORT-SCOPE: Scope 1/2/3 Reports

## API Basic Information

| Item | Content |
|------|---------|
| Unique ID | REPORT-SCOPE |
| API Name | Scope 1/2/3 Reports |
| Type | GET |
| Endpoint | /api/reports/scope |
| Category | Reporting, Dashboard & Audit |
| Status | Planned |

---

## Summary

Detailed reporting for Scope 1, 2, and 3 emissions. GHG Protocol compliant emission reporting.

---

## Scope Definitions

| Scope | Description | Examples |
|-------|-------------|----------|
| Scope 1 | Direct emissions | Company vehicles, on-site fuel |
| Scope 2 | Energy indirect | Purchased electricity, heat |
| Scope 3 | Other indirect | Supply chain, transport |

---

## Scope 3 Categories (15 Total)

| Cat | Category | Priority |
|-----|----------|----------|
| 1 | Purchased Goods & Services | **Critical** |
| 2 | Capital Goods | Medium |
| 3 | Fuel & Energy Related | Medium |
| 4 | Upstream Transport | **Critical** |
| 5 | Waste Generated | Low-Medium |
| 6 | Business Travel | Low |
| 7 | Employee Commuting | Low |
| 8 | Upstream Leased Assets | Low |
| 9 | Downstream Transport | **Critical** |
| 10 | Processing of Sold Products | Medium |
| 11 | Use of Sold Products | Low-Medium |
| 12 | End-of-Life Treatment | Low |
| 13 | Downstream Leased Assets | Low |
| 14 | Franchises | N/A |
| 15 | Investments | Low |

---

## Report Features

- **Separate Analysis**: Each scope independently
- **Category Breakdown**: Within each scope
- **Trend Analysis**: Over time
- **Compliance Format**: Regulatory-ready

---

## Implementation Notes

- GHG Protocol compliant
- Category-level detail
- Export for audits

---

## Related Features

- REPORT-TOTAL (Total CO₂ Emission Report)
- REPORT-CATEGORY (Category-wise Breakdown)
- AUDIT-COMPLIANCE (Compliance Export)