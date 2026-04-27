# IAM-COMP-UPDATE: Company Update

## API Basic Information

| Item | Content |
|------|---------|
| Unique ID | IAM-COMP-UPDATE |
| API Name | Company Update |
| Type | PUT |
| Endpoint | /api/company/:id |
| Category | Identity & Access Management |
| Status | Planned |

---

## Summary

Update company details and settings. Modify company information.

---

## Updatable Fields

| Field | Description |
|-------|-------------|
| Company Name | Legal name |
| Industry | Industry category |
| Address | Business address |
| Contact | Contact information |
| Settings | Company preferences |

---

## Update Process

| Step | Description |
|------|-------------|
| 1 | User edits company |
| 2 | Validate input |
| 3 | Update company record |
| 4 | Log audit trail |
| 5 | Return updated data |

---

## Validation Rules

| Field | Rule |
|--------|------|
| Name | Required, max 100 chars |
| Industry | From predefined list |
| Country | Valid country code |
| Address | Max 500 chars |

---

## API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| /api/company/:id | PUT | Update company |
| /api/company/settings | PUT | Update settings |

---

## Implementation Notes

- Validation on update
- Audit logging
- Settings management

---

## Related Features

- IAM-COMP-GET (Company Get)
- IAM-COMP-LIST (Company List)
- USER-PROFILE (Company Profile)