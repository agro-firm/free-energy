# 02 — Cow Yard

## Documentation status
**Detailed engineering concept package — Section 02 complete for planning.**

## Canonical baseline
- **Plant version:** PLANT-V1.0
- **Footprint:** 18 ft × 28 ft
- **Area:** 504 ft² ≈ 46.82 m²
- **Function:** compact paved exercise/holding yard
- **Recommended simultaneous operating group:** **10 cows**
- **Whole herd:** 20 cows in two rotational groups
- **Active animal zone:** 18 × 24 ft = 432 ft² ≈ 40.13 m²
- **Service/drain zone:** 18 × 4 ft = 72 ft²
- **Shade canopy concept:** 12 × 18 ft = 216 ft² over half of active zone

## Why 10 cows at a time
If all 20 cows occupy the whole 46.82 m²:
```
46.82 / 20 = 2.34 m²/cow
```
For 10 cows in the 40.13 m² active zone:
```
40.13 / 10 = 4.01 m²/cow
```
Therefore the compact yard is documented as a **two-batch rotational space**, not a 20-cow simultaneous exercise yard.

## Document map
| File | Purpose |
|---|---|
| [ARCHITECTURE.md](ARCHITECTURE.md) | open-yard architecture, canopy, fencing, drainage and adjacency |
| [BLUEPRINT.md](BLUEPRINT.md) | X/Y/Z geometry and zone layout |
| [DESIGN.md](DESIGN.md) | animal movement, floor, shade, gates, trough and safety |
| [CALCULATIONS.md](CALCULATIONS.md) | area, capacity, slope, water, fencing and cost math |
| [UTILITIES.md](UTILITIES.md) | dirty drainage, clean canopy runoff, water, electrical/data and gas exclusion |
| [PROCESS.md](PROCESS.md) | rotation, entry/exit, cleaning and abnormal conditions |
| [EQUIPMENT.md](EQUIPMENT.md) | fencing, gates, trough, canopy, drains, lights and sensors |
| [DIAGRAMS.md](DIAGRAMS.md) | plan, flow and utility diagrams |
| [CONSTRUCTION.md](CONSTRUCTION.md) | pavement, drains, posts, canopy and commissioning |
| [OPERATIONS-MAINTENANCE.md](OPERATIONS-MAINTENANCE.md) | daily/seasonal cleaning and maintenance |
| [BENEFITS.md](BENEFITS.md) | welfare, movement, hygiene and operational value |
| [COST.md](COST.md) | 2026 Bangladesh low/base/high budget |
| [IMAGE.md](IMAGE.md) | canonical image math, prompts and QA |
| [images/README.md](images/README.md) | image naming |
| [images/IMAGE-GUIDE.md](images/IMAGE-GUIDE.md) | detailed visual rules |
| [images/VIEW-MATRIX.md](images/VIEW-MATRIX.md) | camera/view checklist |

## Mandatory interfaces
- direct cow connection to Section 01
- water from Section 13
- dirty runoff to approved waste/wastewater handling
- shade-roof rain to clean stormwater
- no biogas line, gas storage or generator equipment in the yard
