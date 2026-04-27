# EF-DEFAULT: Get EF Database

## API Basic Information

| Item | Content |
|------|---------|
| Unique ID | EFM-LIST |
| API Name | Get EF Database |
| Type | GET |
| Endpoint | /api/emissionfactors |
| Category | Emission Factor (EF) Management |
| Status | Planned |

---

## Summary

Retrieve default (IPCC/DEFRA) and custom EFs. Default emission factor database providing standardized factors.

---

## Data Sources

| Source | Description | Coverage |
|--------|-------------|----------|
| IPCC | Intergovernmental Panel on Climate Change | Global |
| DEFRA | UK Department for Environment | International |
| Japan MOE | Ministry of Environment Japan | Japan-specific |
| ecoinvent | Swiss emission factor database | Process-specific |
| IDEA v3 | French emission database | European |

---

## Default Emission Factors

### Transport (kg CO2e/tonne-km)

| Mode | Factor | Notes |
|------|--------|-------|
| Container Ship | 0.01-0.02 | Baseline |
| Rail | 0.03 | 2-3x baseline |
| Road (HGV) | 0.10-0.15 | 8-15x baseline |
| Refrigerated Truck | 0.15-0.25 | 12-25x baseline |
| Air Freight | 0.50-0.60 | 50-60x baseline |

### Energy (kg CO2e/unit)

| Source | Factor | Unit |
|--------|--------|------|
| Electricity (Japan) | 0.457 | kg CO2e/kWh |
| Natural Gas | 2.02 | kg CO2e/m³ |
| Diesel | 2.68 | kg CO2e/liter |
| Gasoline | 2.31 | kg CO2e/liter |
| LPG | 1.51 | kg CO2e/liter |

---

## Implementation Notes

- Automatic factor selection based on activity
- Regularly updated with latest data
- Covers 15 GHG Protocol categories

---

## Related Features

- EF-CUSTOM (Custom EF Management)
- EF-REGION (Region-based EF)
- EF-VERSION (EF Version Control)