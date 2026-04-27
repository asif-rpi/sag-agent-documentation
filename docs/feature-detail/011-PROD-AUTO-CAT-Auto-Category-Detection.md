# PROD-AUTO-CAT: Auto Categorize

## API Basic Information

| Item | Content |
|------|---------|
| Unique ID | INTEL-AUTO |
| API Name | Auto Categorize |
| Type | POST |
| Endpoint | /api/data/categorize |
| Category | Data Input & Intelligence |
| Status | Planned |

---

## Summary

AI-based auto categorization of items. Automatically detect and assign GHG Protocol emission categories.

---

## Supported Categories (GHG Protocol Scope 3)

| Cat # | Category | Priority |
|-------|----------|----------|
| 1 | Purchased Goods & Services | **Critical** |
| 2 | Capital Goods | Medium |
| 3 | Fuel & Energy Related Activities | Medium |
| 4 | Upstream Transportation & Distribution | **Critical** |
| 5 | Waste Generated in Operations | Low-Medium |
| 6 | Business Travel | Low |
| 7 | Employee Commuting | Low |
| 8 | Upstream Leased Assets | Low |
| 9 | Downstream Transportation & Distribution | **Critical** |
| 10 | Processing of Sold Products | Medium |
| 11 | Use of Sold Products | Low-Medium |
| 12 | End-of-Life Treatment | Low |
| 13 | Downstream Leased Assets | Low |
| 14 | Franchises | N/A |
| 15 | Investments | Low |

---

## Detection Process

```
Product Data → ML Model Analysis → Category Prediction → 
Confidence Score → Auto-assign or Manual Review
```

---

## Features

- **ML Learning**: Improves from historical classifications
- **Confidence Scoring**: Shows prediction confidence
- **Manual Override**: Allow manual corrections
- **Batch Processing**: Process multiple products

---

## Implementation Notes

- Reduces manual categorization by ~80%
- Learns from user corrections
- Ensures consistent categorization

---

## Related Features

- PROD-TAXONOMY (Product Taxonomy Mapping)
- PROD-SIMILAR (Similar Item Suggestion)
- BONUS-ML (ML Auto Classification)