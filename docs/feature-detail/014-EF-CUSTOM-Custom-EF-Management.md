# EF-CUSTOM: Custom EF Management

## Feature Basic Information

| Item | Content |
|------|---------|
| Unique ID | EF-CUSTOM |
| Feature Name | Custom EF Management |
| Category | Emission Factor Management |
| Priority | High |
| Implementation Phase | Phase 2 |

---

## Purpose

Custom emission factor management allows organizations to upload and manage their own emission factors, including supplier-specific data.

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