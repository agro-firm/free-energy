# 08 — Biogas Digester

## Documentation status
**Detailed process/civil/biological engineering concept package — Section 08 complete for planning.**

## Canonical baseline
- **Plant version:** PLANT-V1.0
- **Compound:** 16 ft × 20 ft = 320 ft² ≈ 29.73 m²
- **Digester type:** semi-buried cylindrical RCC low-pressure anaerobic digester
- **Total internal volume:** 25 m³
- **Target working liquid volume:** 20 m³
- **Process headspace/freeboard:** ~5 m³
- **Minimum hydraulic volume:** 16.2 m³ at 30-day HRT
- **Target HRT:** ~37 days at 20 m³
- **Planning internal diameter:** 2.8 m ≈ 9.19 ft
- **Planning internal total height:** ~4.06 m ≈ 13.32 ft
- **Planning working liquid depth:** ~3.25 m ≈ 10.66 ft
- **Planning headspace depth:** ~0.81 m ≈ 2.66 ft
- **Daily slurry feed:** ~0.54 m³/day
- **Biogas:** ~8.10–9.18 m³/day
- **Main gas storage:** separate 8 m³ holder in Section 09

## Process
Section 07 → submerged digester feed → anaerobic digestion → gas headspace → condensate protection → Section 09 gas holder.

Digestate displacement/overflow → Section 12 fertilizer/digestate processing.

## Document map
| File | Purpose |
|---|---|
| [ARCHITECTURE.md](ARCHITECTURE.md) | compound, vessel form, burial, service access and environmental architecture |
| [BLUEPRINT.md](BLUEPRINT.md) | exact XYZ geometry, cylinder, inlet/outlet, pits and service zones |
| [DESIGN.md](DESIGN.md) | hydraulic, biological, mixing, gas and digestate design philosophy |
| [CALCULATIONS.md](CALCULATIONS.md) | vessel, HRT, solids, OLR, gas, structural quantities and cost math |
| [UTILITIES.md](UTILITIES.md) | slurry, digestate, gas, condensate, electrical/data and drainage interfaces |
| [PROCESS.md](PROCESS.md) | feeding, digestion, gas release, digestate displacement and abnormal operation |
| [BIOLOGY-STARTUP.md](BIOLOGY-STARTUP.md) | inoculation, startup ramp, pH/temperature/loading and biological monitoring |
| [EQUIPMENT.md](EQUIPMENT.md) | vessel components, valves, recirculation, sensors and safety devices |
| [P&ID.md](P&ID.md) | process/instrumentation tags and line/control concept |
| [AUTOMATION.md](AUTOMATION.md) | feed permissives, recirculation, alarms and PLC integration |
| [SAFETY.md](SAFETY.md) | methane/H₂S, confined space, pressure/vacuum, excavation and fire safety |
| [DIAGRAMS.md](DIAGRAMS.md) | plan, section, hydraulic, gas and control diagrams |
| [CONSTRUCTION.md](CONSTRUCTION.md) | excavation, RCC, gas-tightness, testing and commissioning |
| [OPERATIONS-MAINTENANCE.md](OPERATIONS-MAINTENANCE.md) | daily/weekly/monthly/annual checks and KPIs |
| [BENEFITS.md](BENEFITS.md) | energy, waste, fertilizer and process-stability benefits |
| [COST.md](COST.md) | Bangladesh 2026 planning cost model |
| [IMAGE.md](IMAGE.md) | canonical image geometry, cutaway math, prompts and QA |
| [images/README.md](images/README.md) | image naming/governance |
| [images/IMAGE-GUIDE.md](images/IMAGE-GUIDE.md) | detailed rendering and camera rules |
| [images/VIEW-MATRIX.md](images/VIEW-MATRIX.md) | required external, sectional and process views |

## Public Bangladesh context
IDCOL reports financing both brick-cement and prefabricated biogas plants and states its program covers daily gas-production capacities from roughly 1.2 to 25 m³/day. This project's ~8–9 m³/day gas output falls within that broad program scale.

Reference:
https://www.idcol.org/idcol_new/public/renewable/biogas-and-bio-fertilizer
