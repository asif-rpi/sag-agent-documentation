# IAM-USER-DELETE: User Delete

## API Basic Information

| Item | Content |
|------|---------|
| Unique ID | IAM-USER-DELETE |
| API Name | User Delete |
| Type | DELETE |
| Endpoint | /api/users/:id |
| Category | Identity & Access Management |
| Status | Planned |

---

## Summary

Delete or deactivate user accounts. Remove user from the system.

---

## Delete Options

| Type | Description |
|------|-------------|
| Soft Delete | Deactivate, keep data |
| Hard Delete | Permanent removal |
| Transfer | Transfer ownership |

---

## Delete Process

| Step | Description |
|------|-------------|
| 1 | Admin initiates delete |
| 2 | Check user permissions |
| 3 | Transfer ownership if needed |
| 4 | Deactivate or remove |
| 5 | Log audit trail |
| 6 | Send notification |

---

## Considerations

| Factor | Description |
|--------|-------------|
| Data Retention | Keep emissions data |
| Reports | Archive with company |
| Sessions | Invalidate all sessions |
| Integrations | Remove API keys |

---

## API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| /api/users/:id | DELETE | Delete user |
| /api/users/:id/deactivate | POST | Deactivate user |

---

## Implementation Notes

- Soft delete default
- Data preservation
- Complete audit trail

---

## Related Features

- IAM-USER-LIST (User List)
- IAM-USER-UPDATE (User Update)
- AUDIT-TRAIL (Data Audit Trail)