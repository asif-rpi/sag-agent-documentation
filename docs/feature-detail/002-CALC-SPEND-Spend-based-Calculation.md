# CALC-SPEND: Spend-based Calculation

## API Basic Information

| Item | Content |
|------|---------|
| Unique ID | CALC-SPEND |
| API Name | Spend-based Calculation |
| Type | POST |
| Endpoint | /api/calculate |
| Category | Calculation & Simulation |
| Status | Planned |

---

## Summary

Calculate CO2 emissions based on spend data. Alternative calculation using monetary value.
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