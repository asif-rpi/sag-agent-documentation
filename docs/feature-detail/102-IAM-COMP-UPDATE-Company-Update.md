# IAM-COMP-UPDATE: Company Update

## Feature Basic Information

| Item | Content |
|------|---------|
| Unique ID | IAM-COMP-UPDATE |
| Feature Name | Company Update |
| Category | Identity & Access Management |
| Priority | High |
| Implementation Phase | Phase 1 |

---

## Purpose

Update company details and settings.

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