# USER-PROFILE: Company Profile

## API Basic Information

| Item | Content |
|------|---------|
| Unique ID | USER-PROFILE |
| API Name | Company Profile |
| Type | GET |
| Endpoint | /api/company/profile |
| Category | User & Company Management |
| Status | Planned |

---

## Summary

Manage company information and profiles. Retrieve company settings and details.

---

## Profile Information

| Field | Description |
|-------|-------------|
| Company Name | Legal entity name |
| Industry | Business sector |
| Location | Headquarters address |
| Employees | Company size |
| Fiscal Year | Reporting period |

---

## Profile Sections

| Section | Description |
|---------|-------------|
| Basic Info | Company details |
| Industry | Sector classification |
| Contacts | Admin contacts |
| Compliance | Regulatory info |
| Settings | System preferences |

---

## Compliance Information

| Field | Description |
|-------|-------------|
| Regulatory Framework | Applicable regulations |
| Reporting Period | Fiscal year |
| Verification Status | Third-party verification |
| Certification | ISO certifications |

---

## API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| /api/company/profile | GET | Get profile |
| /api/company/profile | PATCH | Update profile |
| /api/company/logo | POST | Upload logo |

---

## Implementation Notes

- Link to emission reports
- Support multiple profiles
- Validate company data

---

## Related Features

- USER-MULTI (Multi-user System)
- REPORT-TOTAL (Total CO₂ Emission Report)