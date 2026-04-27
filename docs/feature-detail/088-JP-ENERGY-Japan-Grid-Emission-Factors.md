# JP-ENERGY: Japan Grid Emission Factors

## Feature Basic Information

| Item | Content |
|------|---------|
| Unique ID | JP-ENERGY |
| Feature Name | Japan Grid Emission Factors |
| Category | Japan-Native Design |
| Priority | High |
| Implementation Phase | Phase 2 |

---

## Purpose

Japan-specific electricity grid emission factors for accurate Scope 2 calculations.

---

## Japan Grid Factors

| Source | Factor (kg CO2e/kWh) |
|--------|----------------------|
| Tokyo Electric | 0.457 |
| Kansai Electric | 0.389 |
| Chubu Electric | 0.474 |
| Hokkaido Electric | 0.621 |
| Tohoku Electric | 0.372 |
|九州 Electric | 0.412 |

---

## Regional Factors

| Region | Factor | Grid Operator |
|--------|--------|----------------|
| Tokyo | 0.457 | TEPCO |
| Kansai | 0.389 | KEPCO |
| Chubu | 0.474 | Chubu EPC |
| Tohoku | 0.372 | Tohoku EPC |
| Hokkaido | 0.621 | Hokkaido EPC |
|九州 | 0.412 | Kyushu EPC |

---

## Update Schedule

| Update | Frequency |
|--------|-----------|
| Annual | Yearly (April) |
| Regional | As needed |
| Grid Changes | On grid changes |

---

## Features

| Feature | Description |
|---------|-------------|
| Auto-detection | From location |
| Regional Factors | All Japan regions |
| Historical | Past factors |

---

## Implementation Notes

- Japan-specific factors
- Accurate Scope 2
- Regular updates

---

## Related Features

- EF-REGION (Region-based EF)
- CALC-MASS (Mass-based Calculation)
- COMP-SSBJ (Japan SSBJ Compliance Module)