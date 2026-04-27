# JP-TRANSPORT: Japan Domestic Transport

## Feature Basic Information

| Item | Content |
|------|---------|
| Unique ID | JP-TRANSPORT |
| Feature Name | Japan Domestic Transport |
| Category | Japan-Native Design |
| Priority | High |
| Implementation Phase | Phase 2 |

---

## Purpose

Japan domestic logistics emission factors and carrier integration.

---

## Japan Carriers

| Carrier | Type | API |
|---------|------|-----|
| Yamato Transport | Small parcel | ✓ |
| Sagawa Express | Small parcel | ✓ |
| Japan Post | Postal | ✓ |
| Seino Transportation | Freight | ✓ |
| Fukuyama Shipping | Freight | ✓ |

---

## Domestic Factors

| Mode | Factor (kg CO2e/tonne-km) |
|------|--------------------------|
| Truck (Small) | 0.25 |
| Truck (Large) | 0.10 |
| Rail | 0.03 |
| Sea (Coastal) | 0.02 |

---

## Service Types

| Service | Description |
|---------|-------------|
| Ta-Q-Bin | Home delivery |
| Kuroneko | Yamato service |
| Non-presence | Locker delivery |

---

## Features

| Feature | Description |
|---------|-------------|
| Carrier Integration | Real-time tracking |
| Domestic Factors | Japan-specific |
| Last Mile | Final delivery |

---

## Implementation Notes

- Japan domestic focus
- Local carrier APIs
- Domestic logistics

---

## Related Features

- DATA-CONN-CARRIER (Carrier API Integration)
- ROUTE-OPTIMIZE (Route Optimization Engine)
- CALC-MASS (Mass-based Calculation)