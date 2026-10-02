# 07 — Waste Receiving + Mixing

## Documentation status
**Detailed process-engineering concept package — Section 07 complete for planning.**

## Canonical baseline
- **Plant version:** PLANT-V1.0
- **Footprint:** 10 ft × 14 ft
- **Area:** 140 ft² ≈ 13.01 m²
- **Collected fresh dung:** ~270 kg/day
- **Dilution water:** ~270 L/day
- **Total slurry:** ~0.54 m³/day
- **Feed frequency:** 4 automatic batches/day
- **Nominal slurry batch:** ~0.135 m³
- **Receiving sump:** ~0.75 m³ gross / ~0.60 m³ working concept
- **Mixing tank:** 500 L gross / ~350 L working concept, mounted on load cells
- **Emergency holding sump:** ~1.0 m³ gross / ~0.8 m³ working concept
- **Slurry line:** 75 mm / 3-inch-class planning concept
- **Gravity overflow/cleanout:** 100 mm / 4-inch-class planning concept
- **Water dosing line:** 25 mm / 1-inch-class planning concept

## Core process
Cow shed scraper/gutter → coarse debris screen → grit pocket → receiving sump → measured dung batch → mixing tank/load cells → measured water → mixing → digester permissive → slurry pump → electromagnetic flow meter → Section 08 digester.

## Document map
| File | Purpose |
|---|---|
| [ARCHITECTURE.md](ARCHITECTURE.md) | dirty-process architecture, covered bay, drainage, odor and maintenance |
| [BLUEPRINT.md](BLUEPRINT.md) | exact XYZ zones, sumps, tanks, pipes, service access and elevations |
| [DESIGN.md](DESIGN.md) | equipment layout, process philosophy and maintainability |
| [CALCULATIONS.md](CALCULATIONS.md) | mass balance, slurry, tank, pipe, pump, batch and cost math |
| [UTILITIES.md](UTILITIES.md) | water, dirty drainage, slurry piping, electrical/data and ventilation |
| [PROCESS.md](PROCESS.md) | normal process, batch sequence, failures and manual recovery |
| [EQUIPMENT.md](EQUIPMENT.md) | screens, sumps, mixer, pumps, flow meters, sensors and controls |
| [P&ID.md](P&ID.md) | process/instrumentation IDs, valves, pumps and signal definitions |
| [AUTOMATION.md](AUTOMATION.md) | PLC state machine, interlocks, alarms and setpoint philosophy |
| [SAFETY.md](SAFETY.md) | confined-space, H₂S/methane, moving equipment and spill controls |
| [DIAGRAMS.md](DIAGRAMS.md) | plan, process, control and utility diagrams |
| [CONSTRUCTION.md](CONSTRUCTION.md) | civil/process construction, testing and commissioning |
| [OPERATIONS-MAINTENANCE.md](OPERATIONS-MAINTENANCE.md) | daily/weekly/monthly maintenance and KPI logging |
| [BENEFITS.md](BENEFITS.md) | automation, hygiene, digester stability and labor benefits |
| [COST.md](COST.md) | 2026 Bangladesh low/base/high cost model |
| [IMAGE.md](IMAGE.md) | canonical visual geometry, prompt rules and QA |
| [images/README.md](images/README.md) | image naming/governance |
| [images/IMAGE-GUIDE.md](images/IMAGE-GUIDE.md) | detailed camera/prompt guidance |
| [images/VIEW-MATRIX.md](images/VIEW-MATRIX.md) | required process/detail views |

## Mandatory skill references
Use master-plant, engineering-math, manure-automation, biogas-digester, water-drainage, controls-automation, visualization-images, safety-regulatory and construction-review skills before changing this section.
