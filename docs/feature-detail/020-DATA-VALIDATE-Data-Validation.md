# DATA-VALIDATE: Validate Data

## API Basic Information

| Item | Content |
|------|---------|
| Unique ID | DPE-VALIDATE |
| API Name | Validate Data |
| Type | POST |
| Endpoint | /api/data/validate |
| Category | Data Input & Intelligence |
| Status | Planned |

---

## Summary

Pre-calculation validation checks. Comprehensive data validation system ensuring accuracy.

---

## Validation Types

| Type | Description |
|------|-------------|
| Format Validation | Correct data types and formats |
| Range Validation | Values within acceptable ranges |
| Required Fields | All mandatory fields present |
| Consistency | Cross-field relationships valid |
| Business Rules | Custom validation logic |

---

## Validation Rules

| Rule | Check | Action |
|------|-------|--------|
| Quantity > 0 | Positive numbers | Reject if ≤ 0 |
| Valid Unit | In unit list | Reject if unknown |
| Date Range | Within project period | Warn if outside |
| Amount > 0 | Positive values | Reject if negative |
| Category Valid | GHG category exists | Reject if invalid |

---

## Validation Process

```
Data Input → Format Check → Required Fields → 
Range Check → Business Rules → Validation Report
```

---

## Validation Report

| Field | Status |
|-------|--------|
| Total Records | Count |
| Valid Records | Passed all checks |
| Warnings | Minor issues |
| Errors | Must fix before processing |
| Validation Rate | % passing |

---

## Implementation Notes

- Flags anomalies before calculation
- Configurable validation rules
- Detailed error messages

---

## Related Features

- DATA-CLEAN (Auto Data Cleaning)
- DATA-MISSING (Missing Data Handling)
- AUDIT-TRAIL (Data Audit Trail)