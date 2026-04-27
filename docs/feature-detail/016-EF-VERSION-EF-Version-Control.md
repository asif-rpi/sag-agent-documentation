# EF-VERSION: Update Custom EF

## API Basic Information

| Item | Content |
|------|---------|
| Unique ID | EFM-UPDATE |
| API Name | Update Custom EF |
| Type | PATCH |
| Endpoint | /api/emissionfactors/:id |
| Category | Emission Factor (EF) Management |
| Status | Planned |

---

## Summary

Update existing custom EF details. Version control maintains historical versions of emission factors.

---

## Version Control Features

| Feature | Description |
|---------|-------------|
| Version History | Track all factor changes |
| Rollback | Revert to previous versions |
| Comparison | Compare versions side-by-side |
| Documentation | Document change reasons |

---

## Version Schema

```
EF-{Category}-{Region}-{Version}
Example: EF-TRANSPORT-JP-v2.1
```

---

## Version Information

| Field | Description |
|-------|-------------|
| Version ID | Unique version identifier |
| Effective Date | When version became active |
| Expiry Date | When version was superseded |
| Change Reason | Why factor was updated |
| Source | Data source for update |
| Approved By | Who approved change |

---

## Audit Trail

| Action | Record |
|--------|--------|
| Create | New factor added |
| Update | Factor modified |
| Archive | Factor deactivated |
| Restore | Archived factor reactivated |

---

## Implementation Notes

- Supports regulatory requirements
- Maintains calculation consistency
- Full audit trail for compliance

---

## Related Features

- EF-DEFAULT (Default EF Database)
- EF-CUSTOM (Custom EF Management)
- AUDIT-TRAIL (Data Audit Trail)