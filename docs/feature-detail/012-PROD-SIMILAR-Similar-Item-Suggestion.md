# PROD-SIMILAR: Similar Item Suggestion

## API Basic Information

| Item | Content |
|------|---------|
| Unique ID | PROD-SIMILAR |
| API Name | Similar Item Suggestion |
| Type | POST |
| Endpoint | /api/data/similar |
| Category | Data Input & Intelligence |
| Status | Planned |

---

## Summary

Find comparable products in the database. AI-powered similar item suggestion system.

---

## Similarity Types

| Type | Description |
|------|-------------|
| Product Similarity | Same product category |
| Emission Profile | Similar CO2e characteristics |
| Supply Chain | Similar supplier/transport |
| Material Composition | Same raw materials |

---

## Use Cases

| Use Case | Description |
|----------|-------------|
| Benchmarking | Compare carbon performance |
| Supplier Finding | Find alternative suppliers |
| Category Consistency | Ensure uniform categorization |
| Price/Emission Trade-off | Analyze cost vs emissions |

---

## Suggestion Algorithm

```
Product Profile → Feature Extraction → Similarity Scoring → 
Rank Results → Display Suggestions
```

---

## Features

- **Multiple Criteria**: Product, emission, supply chain
- **Ranking**: Most similar first
- **Filtering**: Filter by category/metric
- **Quick Apply**: Apply suggestion to product

---

## Implementation Notes

- ML-based similarity detection
- Helps reduce categorization errors
- Supports emission benchmarking

---

## Related Features

- PROD-TAXONOMY (Product Taxonomy Mapping)
- PROD-AUTO-CAT (Auto Category Detection)
- BONUS-ML (ML Auto Classification)