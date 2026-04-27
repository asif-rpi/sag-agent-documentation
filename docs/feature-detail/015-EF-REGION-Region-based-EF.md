# EF-REGION: Region-based EF

## API Basic Information

| Item | Content |
|------|---------|
| Unique ID | EF-REGION |
| API Name | Region-based EF |
| Type | GET |
| Endpoint | /api/emissionfactors/region |
| Category | Emission Factor (EF) Management |
| Status | Planned |

---

## Summary

Get region-specific emission factors. Region-specific emission factors for local energy grids.

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