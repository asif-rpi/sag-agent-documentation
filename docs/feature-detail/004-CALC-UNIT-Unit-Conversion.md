# CALC-UNIT: Unit Conversion

## Feature Basic Information

| Item | Content |
|------|---------|
| Unique ID | CALC-UNIT |
| Feature Name | Unit Conversion |
| Category | Core Carbon Calculation Engine |
| Priority | High |
| Implementation Phase | Phase 2 |

---

## Purpose

Unit Conversion feature handles automatic conversion between different units of measurement for quantities and emission factors. This ensures consistent calculations regardless of the input unit system.

---

## Supported Unit Types

### Mass/Weight Units

| Unit | Symbol | Conversion to kg |
|------|--------|------------------|
| Kilogram | kg | 1 |
| Gram | g | 0.001 |
| Metric Ton | t | 1000 |
| Pound | lb | 0.453592 |
| Ounce | oz | 0.0283495 |

### Distance Units

| Unit | Symbol | Conversion to km |
|------|--------|------------------|
| Kilometer | km | 1 |
| Meter | m | 0.001 |
| Mile | mi | 1.60934 |
| Nautical Mile | nmi | 1.852 |

### Volume Units

| Unit | Symbol | Conversion to L |
|------|--------|------------------|
| Liter | L | 1 |
| Milliliter | mL | 0.001 |
| Gallon (US) | gal | 3.78541 |
| Cubic Meter | m³ | 1000 |

### Energy Units

| Unit | Symbol | Conversion to kWh |
|------|--------|-------------------|
| Kilowatt-hour | kWh | 1 |
| Joule | J | 0.000000277778 |
| BTU | BTU | 0.000293071 |
| Calorie | cal | 0.00000116222 |

---

## Conversion Formula

```
Converted Value = Input Value × Conversion Factor
```

---

## Implementation Notes

- Supports both metric and imperial unit systems
- Automatic detection of input units
- Validation to ensure units are compatible with calculation type

---

## Related Features

- CALC-MASS (Mass-based Calculation)
- CALC-SPEND (Spend-based Calculation)
- CALC-DUAL (Dual Mode Calculation)