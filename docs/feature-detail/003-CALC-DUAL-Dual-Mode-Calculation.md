# CALC-DUAL: Dual Mode Calculation

## Feature Basic Information

| Item | Content |
|------|---------|
| Unique ID | CALC-DUAL |
| Feature Name | Dual Mode Calculation |
| Category | Core Carbon Calculation Engine |
| Priority | High |
| Implementation Phase | Phase 2 |

---

## Purpose

Dual Mode Calculation allows the system to automatically switch between mass-based and spend-based calculation methods based on data availability. This provides flexibility and ensures carbon calculations can proceed even with incomplete data.

---

## How It Works

```
Order Data → Check Data Availability 
→ If mass/quantity available → Use Mass-based Calculation
→ If only spend value available → Use Spend-based Calculation
→ If both available → Use Hybrid (most accurate)
```

---

## Hybrid Calculation Approach

When both mass and spend data are available, the system uses a hybrid approach for highest accuracy:

| Data Available | Method Used | Accuracy |
|----------------|-------------|----------|
| Mass + EF | Mass-based | High |
| Spend only | Spend-based | Low |
| Both | Hybrid | Highest |

---

## Implementation Notes

- Automatically detects which calculation method to use
- Falls back to spend-based when mass data is unavailable
- Supports transition from spend-based to mass-based as more data becomes available

---

## Related Features

- CALC-MASS (Mass-based Calculation)
- CALC-SPEND (Spend-based Calculation)
- CALC-UNIT (Unit Conversion)