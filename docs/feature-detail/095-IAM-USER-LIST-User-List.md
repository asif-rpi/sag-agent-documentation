# IAM-USER-LIST: User List

## Feature Basic Information

| Item | Content |
|------|---------|
| Unique ID | IAM-USER-LIST |
| Feature Name | User List |
| Category | Identity & Access Management |
| Priority | High |
| Implementation Phase | Phase 1 |

---

## Purpose

List and manage users within a company.

---

## User List Features

| Feature | Description |
|---------|-------------|
| Pagination | Page through users |
| Filtering | Filter by role/status |
| Sorting | Sort by name/date |
| Search | Search by name/email |

---

## User Data

| Field | Description |
|-------|-------------|
| User ID | Unique identifier |
| Email | User email |
| Name | Full name |
| Role | User role |
| Status | Active/Inactive |
| Created | Registration date |

---

## API Parameters

| Parameter | Description |
|-----------|-------------|
| page | Page number |
| limit | Items per page |
| role | Filter by role |
| status | Filter by status |
| search | Search query |

---

## API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| /api/users | GET | List users |
| /api/users/:id | GET | Get user |
| /api/users | POST | Create user |
| /api/users/:id | PUT | Update user |

---

## Implementation Notes

- Company-scoped users
- Role-based filtering
- Pagination support

---

## Related Features

- AUTH-LOGIN (User Login)
- IAM-USER-ROLE (User Role Management)
- USER-ROLE (Role-based Access)