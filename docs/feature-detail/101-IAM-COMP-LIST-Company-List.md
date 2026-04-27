# IAM-COMP-LIST: Company List

## Feature Basic Information

| Item | Content |
|------|---------|
| Unique ID | IAM-COMP-LIST |
| Feature Name | Company List |
| Category | Identity & Access Management |
| Priority | High |
| Implementation Phase | Phase 1 |

---

## Purpose

List all companies (for super admin).

---

## Company List Features

| Feature | Description |
|---------|-------------|
| Pagination | Page through companies |
| Filtering | Filter by industry/country |
| Sorting | Sort by name/date |
| Search | Search by name |

---

## Company Data

| Field | Description |
|-------|-------------|
| Company ID | Unique identifier |
| Company Name | Legal name |
| Industry | Industry category |
| Country | Location country |
| Users | User count |
| Status | Active/Inactive |

---

## API Parameters

| Parameter | Description |
|-----------|-------------|
| page | Page number |
| limit | Items per page |
| industry | Filter by industry |
| country | Filter by country |
| search | Search query |

---

## API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| /api/admin/companies | GET | List companies |
| /api/admin/companies/:id | GET | Get company |

---

## Implementation Notes

- Admin-only access
- Full company listing
- Pagination support

---

## Related Features

- IAM-COMP-GET (Company Get)
- IAM-COMP-UPDATE (Company Update)
- IAM-USER-LIST (User List)