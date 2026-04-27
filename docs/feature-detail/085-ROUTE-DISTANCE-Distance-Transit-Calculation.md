# ROUTE-DISTANCE: Distance & Transit Calculation

## Feature Basic Information

| Item | Content |
|------|---------|
| Unique ID | ROUTE-DISTANCE |
| Feature Name | Distance & Transit Calculation |
| Category | Route & Supply Chain Optimization |
| Priority | High |
| Implementation Phase | Phase 2 |

---

## Purpose

Calculate accurate distances and transit times for emission calculations.

---

## Distance Methods

| Method | Description |
|--------|-------------|
| Great Circle | Shortest distance |
| Road Distance | Actual road route |
| Rail Distance | Rail network |
| Sea Distance | Maritime routes |

---

## Transit Time Factors

| Factor | Impact |
|--------|--------|
| Distance | Primary |
| Transport Mode | Speed variation |
| Border Crossings | Customs delays |
| Weather | Seasonal delays |

---

## Distance Sources

| Source | Coverage |
|--------|-----------|
| Google Maps | Road |
| Rail Networks | Rail |
| Maritime Routes | Sea |
| Carrier APIs | Actual routes |

---

## Calculation

| Metric | Formula |
|--------|---------|
| Road Distance | Route × EF (road) |
| Sea Distance | Route × EF (sea) |
| Rail Distance | Route × EF (rail) |
| Air Distance | Route × EF (air) |

---

## Implementation Notes

- Accurate distance calculation
- Multiple routing options
- Real-time updates

---

## Related Features

- CALC-MASS (Mass-based Calculation)
- ROUTE-OPTIMIZE (Route Optimization Engine)
- DATA-CONN-CARRIER (Carrier API Integration)