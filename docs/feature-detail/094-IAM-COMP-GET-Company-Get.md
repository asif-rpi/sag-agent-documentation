# IAM-COMP-GET: Get Company Profile

## API Basic Information

| Item | Content |
|------|---------|
| Unique ID | IAM-COMP-GET |
| API Name | Get Company Profile |
| Type | GET |
| Endpoint | /api/company/profile |
| Category | Authentication & User Management |
| Status | Planned |

---

## Summary

Retrieve company settings and details.

---

## Company Data

| Field | Description |
|-------|-------------|
| Company ID | Unique identifier |
| Company Name | Legal name |
| Industry | Industry category |
| Country | Location country |
| Settings | Company preferences |

---

## API Response

```json
{
  "companyId": "comp_123",
  "name": "Acme Corp",
  "industry": "Manufacturing",
  "country": "Japan",
  "settings": {
    "timezone": "Asia/Tokyo",
    "currency": "JPY"
  }
}
```

---

## Access Control

| Role | Access |
|------|--------|
| Admin | Full access |
| Manager | Read/Update |
| User | Read only |

---

## API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| /api/company/:id | GET | Get company |
| /api/company/settings | GET | Get settings |

---

## Implementation Notes

- Company-scoped data
- Settings management
- Multi-company support

---

## Related Features

- AUTH-LOGIN (User Login)
- USER-PROFILE (Company Profile)
- IAM-USER-LIST (User List)