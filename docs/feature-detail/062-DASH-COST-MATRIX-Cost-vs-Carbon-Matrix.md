# DASH-COST-MATRIX: Cost vs. Carbon Matrix

## Feature Basic Information

| Item | Content |
|------|---------|
| Unique ID | DASH-COST-MATRIX |
| Feature Name | Cost vs. Carbon Matrix |
| Category | Dashboard & Visualization |
| Priority | High |
| Implementation Phase | Phase 3 |

---

## Purpose

Interactive scatter plot jeta Cost (¥) vs Carbon Savings (kg CO2e) dekhabe prottek alternative route/supplier-er jonno.

---

## Matrix Display

| Axis | Description |
|------|-------------|
| X-Axis | Cost (¥) |
| Y-Axis | Carbon Savings (kg CO2e) |
| Bubble Size | Total volume |
| Color | Category/mode |

---

## Example Analysis

| Scenario | Cost Impact | Carbon Savings |
|----------|--------------|-----------------|
| Supplier B | +¥5,000 | -200 kg CO2e |
| Route Change | +¥2,000 | -150 kg CO2e |
| Mode Shift | +¥10,000 | -500 kg CO2e |

---

## Decision Rules

| Rule | Description |
|------|-------------|
| Auto-approve | Savings > X% & cost increase < Y% |
| Review | Medium impact |
| Reject | High cost, low savings |

---

## Features

| Feature | Description |
|---------|-------------|
| Interactive Plot | Zoom, filter |
| Recommendations | Best options |
| Scenario Compare | Side-by-side |
| Export | Data export |

---

## Implementation Notes

- Support decision making
- Trade-off visualization
- Configurable thresholds

---

## Related Features

- SCENARIO-WHATIF (What-if Simulation)
- DASH-SUPPLIER (Supplier-Level Emission View)
- DASH-ROUTE (Route-Level Emission View)