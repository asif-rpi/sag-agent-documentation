# SCENARIO-WHATIF - What-if Simulation

## Overview
This feature provides scenario analysis capabilities to simulate emission changes based on hypothetical changes.

## Category
Scenario Analysis

## Description
- Simulate "what if" scenarios (e.g., switching plastic to paper)
- Calculate potential emission reductions
- Compare different material choices
- Visualize impact on total emissions

## API Endpoints
- POST /api/scenarios/simulate
- GET /api/scenarios/list

## Implementation Notes
- Store baseline and scenario data
- Calculate differences
- Support multiple variables

## Related Features
- CALC-DUAL (Dual Mode Calculation)
- REPORT-CHARTS (Charts and Trends)