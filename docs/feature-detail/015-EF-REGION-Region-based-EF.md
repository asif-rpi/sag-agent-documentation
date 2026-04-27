# EF-REGION: Region-based EF

## Feature Basic Information

| Item | Content |
|------|---------|
| Unique ID | EF-REGION |
| Feature Name | Region-based EF |
| Category | Emission Factor Management |
| Priority | High |
| Implementation Phase | Phase 2 |

---

## Purpose

Region-specific emission factors that reflect local energy grids, transportation infrastructure, and industrial processes for global supply chains.

---

## Supported Regions

| Region | Grid Factor (kg CO2e/kWh) | Notes |
|--------|--------------------------|-------|
| Japan | 0.457 | Tokyo Electric |
| USA | 0.417 | Average |
| EU | 0.276 | Average |
| China | 0.581 | Coal-heavy |
| India | 0.708 | Coal-heavy |
| Singapore | 0.408 | City-state |

---

## Transport Regional Factors

| Route Type | Factor Adjustment |
|------------|-------------------|
| Domestic (Japan) | Base factors |
| International (Asia) | +10-20% |
| Trans-Pacific | +15-25% |
| Intra-EU | Base factors |

---

## Auto-Detection Logic

```
Origin Location → Determine Region → Apply Grid Factor
→ Check Transport Route → Apply Transport Factor
→ Calculate with Regional Adjustments
```

---

## Features

- **Location-based**: Auto-apply based on addresses
- **Route-aware**: Consider transport corridors
- **Grid updates**: Reflect latest energy mix
- **Custom regions**: Add new regions as needed

---

## Implementation Notes

- Improves accuracy for global supply chains
- Reflects local energy grid variations
- Supports customs compliance

---

## Related Features

- EF-DEFAULT (Default EF Database)
- EF-CUSTOM (Custom EF Management)
- EF-VERSION (EF Version Control)