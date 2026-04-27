# PROD-TAXONOMY: Product Taxonomy Mapping

## Feature Basic Information

| Item | Content |
|------|---------|
| Unique ID | PROD-TAXONOMY |
| Feature Name | Product Taxonomy Mapping |
| Category | AI Agentic Intelligence |
| Priority | Critical |
| Implementation Phase | Phase 2 |

---

## Purpose

SAGBRAIN-er 30M item BRP-Code product taxonomy ke GHG Protocol emission categories-er sathe map korbe. Machine learning model train kora hobe historical data use kore, ar IPCC/DEFRA/MOE database-er emission factors ke BRP-Code hierarchy-te assign kora hobe.

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