# CALC-SPEND: Spend-based Calculation

## Feature Basic Information

| Item | Content |
|------|---------|
| Unique ID | CALC-SPEND |
| Feature Name | Spend-based Calculation |
| Category | Core Carbon Calculation Engine |
| Priority | High |
| Implementation Phase | Phase 2 |

---

## Purpose

Spend-based calculation provides a quick estimation approach for carbon emissions by using purchase values and economy-wide emission factors. This method is particularly useful for initial assessments or when detailed activity data is not yet available.

**Formula:**
```
CO2 = Purchase Value (¥) × EEIO Emission Factor (kg CO2e/¥)
```

**Alternative Weight-Based Formula:**
```
CO2 = Material Weight (kg) × Material-Specific Emission Factor (kg CO2e/kg)
```

---

## When to Use Spend-Based Method

| Scenario | Recommended Method |
|----------|-------------------|
| Starting point / quickest | Spend-Based |
| Supplier data unavailable | Average-Data |
| Transitioning to actuals | Hybrid |
| Supplier provides primary data | Supplier-Specific |

---

## EEIO Emission Factors

| Category | Emission Factor (kg CO2e/¥) |
|----------|---------------------------|
| Manufacturing | 0.0012 |
| Transport | 0.0008 |
| Services | 0.0005 |
| Energy | 0.0015 |

---

## Implementation Notes

- Less accurate than supplier-specific or process-specific methods
- Serves as a valuable starting point for companies beginning their carbon accounting journey
- Use for initial assessments, then migrate to more accurate methods as data becomes available

---

## Related Features

- CALC-MASS (Mass-based Calculation)
- CALC-DUAL (Dual Mode Calculation)
- EF-DEFAULT (Default EF Database)