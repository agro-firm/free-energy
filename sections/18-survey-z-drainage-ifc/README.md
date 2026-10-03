# 18 — Survey, Z-Level, Drainage & IFC Validation

## Status
**Engineering framework complete. Field survey data is still pending.**

Section 17 froze DCF-1 X/Y coordinates. Section 18 defines exactly how real field elevations, rainfall/drainage, flood protection, cut/fill and construction tolerances convert that layout into an IFC site plan.

## What is fixed
- Plot: 65×95 ft.
- DCF-1 X/Y rectangles.
- East service lane X51–65.
- Section interfaces and functional buffers.

## What is not fabricated
- Surveyed RLs.
- Existing ground contours.
- Public-road level.
- Drain outfall invert.
- Flood/high-water level.
- Groundwater level.
- Longitudinal site grade.

Those values must come from field work.

## Key planning checks
- Plot area =573.68 m² =0.05737 ha.
- 100 mm/h conservative drainage screening case with runoff coefficient 0.90 gives ~14.34 L/s full-site runoff.
- 200 mm smooth-pipe screening capacity at 1% grade is ~32.8 L/s full-flow using Manning n≈0.013.
- Section 14 crossfall remains 1.5%, giving ~64 mm fall across the 14-ft lane.
- Clean/critical finished floors use flood/freeboard rules, not a single arbitrary absolute elevation.

## Files
- SURVEY-BRIEF.md
- SURVEY-POINT-REGISTER.md
- SURVEY-DATA-TEMPLATE.csv
- BENCHMARK-DATUM.md
- DESIGN-LEVEL-FRAMEWORK.md
- FINISHED-FLOOR-LEVELS.md
- FLOOD-FREEBOARD.md
- DRAINAGE-HYDROLOGY.md
- DRAINAGE-HYDRAULICS.md
- DRAIN-INVERT-REGISTER.md
- OUTFALL-DECISION.md
- EARTHWORK-CUTFILL.md
- ROAD-GATE-LEVELS.md
- UTILITY-CROSSING-LEVELS.md
- FIELD-QA-QC.md
- SURVEY-TOLERANCES.md
- IFC-VALIDATION.md
- AS-BUILT.md
- COST.md
- REFERENCES.md
- MASTER-DIAGRAMS.md
- IMAGE.md
- images/
