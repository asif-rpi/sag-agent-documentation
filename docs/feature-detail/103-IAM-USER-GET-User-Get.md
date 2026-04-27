# IAM-USER-GET: User Get

## Feature Basic Information

| Item | Content |
|------|---------|
| Unique ID | IAM-USER-GET |
| Feature Name | User Get |
| Category | Identity & Access Management |
| Priority | High |
| Implementation Phase | Phase 1 |

---

## Purpose

Retrieve individual user details.

---

## User Data

| Field | Description |
|-------|-------------|
| User ID | Unique identifier |
| Email | User email |
| Full Name | Full name |
| Role | User role |
| Department | Department |
| Status | Active/Inactive |
| Created | Registration date |
| Last Login | Last login time |

---

## API Response

```json
{
  "userId": "usr_123",
  "email": "user@example.com",
  "name": "John Doe",
  "role": "Manager",
  "department": "Operations",
  "status": "active",
  "created": "2024-01-15T00:00:00Z",
  "lastLogin": "2024-03-20T10:30:00Z"
}
```

---

## Access Control

| Role | Access |
|------|--------|
| Admin | View all users |
| Manager | View team users |
| User | View self |

---

## API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| /api/users/:id | GET | Get user |
| /api/users/me | GET | Get current user |

---

## Implementation Notes

- User-specific data
- Role-based access
- Last login tracking

---

## Related Features

- IAM-USER-LIST (User List)
- IAM-USER-ROLE (User Role Management)
- AUTH-LOGIN (User Login)