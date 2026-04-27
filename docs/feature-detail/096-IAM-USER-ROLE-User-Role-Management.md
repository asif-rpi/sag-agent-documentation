# IAM-USER-ROLE: Update User Role

## API Basic Information

| Item | Content |
|------|---------|
| Unique ID | IAM-USER-ROLE |
| API Name | Update User Role |
| Type | PATCH |
| Endpoint | /api/users/:id/role |
| Category | Authentication & User Management |
| Status | Planned |

---

## Summary

Update RBAC permissions (Admin/User). Assign and manage user roles within a company.

---

## Default Roles

| Role | Description | Permissions |
|------|-------------|--------------|
| Admin | Company admin | Full access |
| Manager | Team manager | Manage team |
| User | Standard user | View/Edit own |
| Viewer | Read-only | View only |

---

## Role Permissions

| Permission | Admin | Manager | User | Viewer |
|------------|-------|---------|------|--------|
| View emissions | ✓ | ✓ | ✓ | ✓ |
| Edit data | ✓ | ✓ | ✓ | ✗ |
| Manage users | ✓ | ✓ | ✗ | ✗ |
| Company settings | ✓ | ✗ | ✗ | ✗ |
| Export reports | ✓ | ✓ | ✓ | ✗ |

---

## Role Assignment

| Action | Description |
|--------|-------------|
| Assign | Set user role |
| Update | Change role |
| Revoke | Remove access |

---

## API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| /api/roles | GET | List roles |
| /api/users/:id/role | PUT | Assign role |
| /api/permissions | GET | List permissions |

---

## Implementation Notes

- Role-based access control
- Company-scoped roles
- Audit role changes

---

## Related Features

- IAM-USER-LIST (User List)
- USER-ROLE (Role-based Access)
- AUTH-LOGIN (User Login)