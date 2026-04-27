# PROD-TAXONOMY: Product Taxonomy Mapping

## API Basic Information

| Item | Content |
|------|---------|
| Unique ID | PROD-TAXONOMY |
| API Name | Product Taxonomy Mapping |
| Type | POST |
| Endpoint | /api/data/taxonomy |
| Category | Data Input & Intelligence |
| Status | Planned |

---

## Summary

Map products to GHG Protocol categories. Automatically detect and assign emission categories to products.

---

## How Mapping Works

```
Product ordered on DOG → BRP-Code identified (from 30M taxonomy) 
→ BRP-Code mapped to emission category → Emission Factor DB queried 
→ Matched factor applied → CO2e calculated
```

---

## Three-Layer Factor Approach

| Layer | Type | Source |
|-------|------|--------|
| Layer 1 (Best) | Supplier-specific | Direct supplier data |
| Layer 2 (Good) | Process-specific | ecoinvent / IDEA v3 |
| Layer 3 (Fallback) | Industry-average | IPCC / DEFRA / Japan MOE |

---

## BRP-Code Structure

| Level | Description |
|-------|-------------|
| Level 1 | Category (e.g., Chemicals) |
| Level 2 | Sub-category (e.g., Reagents) |
| Level 3 | Product Type (e.g., Laboratory Chemicals) |
| Level 4 | Specific Product |

---

## Implementation Notes

- 30 million product items in taxonomy
- ML-based historical matching
- Automatic emission category assignment

---

## Related Features

- PROD-AUTO-CAT (Auto Category Detection)
- EF-DEFAULT (Default EF Database)
- BONUS-ML (ML Auto Classification)