# SCENARIO-WHATIF: What-if Simulation

## Feature Basic Information

| Item | Content |
|------|---------|
| Unique ID | SCENARIO-WHATIF |
| Feature Name | What-if Simulation |
| Category | Reporting & Analytics |
| Priority | High |
| Implementation Phase | Phase 3 |

---

## Purpose

Scenario analysis capabilities to simulate emission changes based on hypothetical changes. Helps in strategic planning for emission reduction.

---

## Simulation Types

| Type | Description |
|------|-------------|
| Material Change | Switch between materials (plastic → paper) |
| Supplier Change | Different supplier with different EF |
| Transport Change | Mode shift (air → sea) |
| Quantity Change | Order volume adjustments |
| Route Change | Different shipping routes |

---

## Simulation Parameters

| Parameter | Description |
|-----------|-------------|
| Baseline | Current emission level |
| Scenario | Proposed change |
| Duration | Simulation period |
| Variables | Factors to change |

---

## What-if Examples

| Scenario | Potential Reduction |
|----------|-------------------|
| Switch air to sea freight | 40-50% transport emissions |
| Change supplier to local | 20-30% logistics emissions |
| Reduce packaging weight | 10-15% packaging emissions |
| Switch to renewable energy | 100% Scope 2 reduction |

---

## API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| /api/scenarios/simulate | POST | Run simulation |
| /api/scenarios/list | GET | List saved scenarios |
| /api/scenarios/:id | GET | Get scenario details |

---

## Implementation Notes

- Compare multiple scenarios
- Visualize impact on totals
- Save for future reference

---

## Related Features

- CALC-DUAL (Dual Mode Calculation)
- REPORT-CHARTS (Charts and Trends)