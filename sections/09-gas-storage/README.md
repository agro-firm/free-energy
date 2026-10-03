# 09 — Gas Storage

## Documentation status
**Detailed gas-process engineering concept package — Section 09 complete for planning.**

## Canonical baseline
- **Plant version:** PLANT-V1.0
- **Zone:** 10 ft × 12 ft = 120 ft² ≈ 11.15 m²
- **Nominal gas capacity:** 8 m³
- **Stored gas:** raw biogas after primary condensate protection, before Section 10 H₂S treatment
- **Baseline holder:** custom low-pressure flexible membrane gas bag inside ventilated galvanized protective frame
- **Membrane:** PVC/PVDF/TPU-coated reinforced fabric, H₂S/UV/gas-permeability rating by vendor
- **Planning inflated membrane envelope:** about 2.0 m × 2.0 m × 2.0 m equivalent
- **Protective enclosure concept:** about 2.4 m × 2.4 m × 2.4 m
- **75% demand-enable:** 6.0 m³
- **20% low cutout:** 1.6 m³
- **Normal usable swing:** 4.4 m³
- **Full-holder production coverage:** ~20.9–23.7 hours at 9.18–8.10 m³/day
- **Normal gas pressure:** very low pressure; final absolute operating pressure is VENDOR/ENGINEER
- **Gas outlet:** DN40 / 1.5-inch-class planning concept
- **Gas route:** Section 08 → condensate → Section 09 → Section 10

## Why a flexible holder
For this small 8 m³ capacity, public industrial double-membrane products often start around 20–50 m³ or larger. Small PVC/TPU biogas bags/balloons around 6–10 m³ are commercially available. The project therefore uses a protected small flexible membrane holder as the baseline and allows a custom double-membrane equivalent if technically/economically justified.

## Document map
| File | Purpose |
|---|---|
| [ARCHITECTURE.md](ARCHITECTURE.md) | zone, protective enclosure, foundation, ventilation and service access |
| [BLUEPRINT.md](BLUEPRINT.md) | exact local XYZ layout, holder envelope, manifold and sensor positions |
| [DESIGN.md](DESIGN.md) | storage philosophy, membrane, pressure, inventory and gas-routing design |
| [CALCULATIONS.md](CALCULATIONS.md) | storage hours, control swing, gas velocity, enclosure and cost math |
| [UTILITIES.md](UTILITIES.md) | raw-gas piping, condensate, power/data, earthing and vent/flare interfaces |
| [PROCESS.md](PROCESS.md) | filling, withdrawal, high/low conditions and abnormal operation |
| [EQUIPMENT.md](EQUIPMENT.md) | membrane, frame, sensors, valves, relief, gas detector and controls |
| [P&ID.md](P&ID.md) | tagged gas-line and safety/instrumentation concept |
| [AUTOMATION.md](AUTOMATION.md) | level-based storage control, permissives, alarms and shutdowns |
| [SAFETY.md](SAFETY.md) | methane/H₂S, pressure/vacuum, fire, lightning and maintenance safety |
| [DIAGRAMS.md](DIAGRAMS.md) | plan, gas inventory, vent/flare and control diagrams |
| [CONSTRUCTION.md](CONSTRUCTION.md) | slab/frame/membrane installation, testing and commissioning |
| [OPERATIONS-MAINTENANCE.md](OPERATIONS-MAINTENANCE.md) | inspection, leak tests, condensate, membrane and sensor maintenance |
| [BENEFITS.md](BENEFITS.md) | buffering, generator cycling, gas recovery and process benefits |
| [COST.md](COST.md) | Bangladesh 2026 planning cost model |
| [IMAGE.md](IMAGE.md) | canonical image geometry, prompts and QA |
| [images/README.md](images/README.md) | image naming/governance |
| [images/IMAGE-GUIDE.md](images/IMAGE-GUIDE.md) | rendering/camera instructions |
| [images/VIEW-MATRIX.md](images/VIEW-MATRIX.md) | required exterior/cutaway/process views |

## Public product context
Public 2026 sources show:
- double-membrane holders commonly described as low-pressure systems around a few mbar, with many vendors focused on much larger capacities;
- 10 m³ double-layer PVC biogas balloons are commercially listed in South Asia;
- 10 m³ PVC/TPU gas bags are listed globally at a few hundred to about US$1,000 for membrane-only products.

Those prices do **not** include the project's protective frame, slab, hazardous-area controls, valves, relief system, gas detection, import/logistics or commissioning.
