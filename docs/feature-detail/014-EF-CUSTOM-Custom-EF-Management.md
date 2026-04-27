# EF-CUSTOM: Add Custom EF

## API Basic Information

| Item | Content |
|------|---------|
| Unique ID | EFM-CREATE |
| API Name | Add Custom EF |
| Type | POST |
| Endpoint | /api/emissionfactors |
| Category | Emission Factor (EF) Management |
| Status | Planned |

---

## Summary

Add a new custom emission factor. Custom emission factor management allows organizations to upload their own factors.

---

## Custom Factor Types

| Type | Description | Priority |
|------|-------------|----------|
| Supplier-Specific | Direct from supplier data | Highest |
| Process-Specific | Company-specific processes | High |
| Product-Specific | Custom product factors | Medium |
| Facility-Specific | Site-specific emissions | Medium |

---

## Custom Factor Validation

| Check | Description |
|-------|-------------|
| Format Validation | Correct data structure |
| Range Validation | Within reasonable bounds |
| Source Verification | Documented source |
| Comparison Check | vs default factors |

---

## Management Features

| Feature | Description |
|---------|-------------|
| Upload | Import custom factors via CSV/Excel |
| Edit | Modify existing factors |
| Archive | Deactivate old factors |
| Audit Trail | Track all changes |

---

## Implementation Notes

- Validate against industry standards
- Version control for all custom data
- Audit trail for compliance

---

## Related Features

- EF-DEFAULT (Default EF Database)
- EF-REGION (Region-based EF)
- AUDIT-TRAIL (Data Audit Trail)