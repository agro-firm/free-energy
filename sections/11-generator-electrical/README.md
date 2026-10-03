# 11 — Generator + Electrical

## Documentation status
**Detailed mechanical/electrical/control engineering concept package — Section 11 complete for planning.**

## Canonical baseline
- **Plant version:** PLANT-V1.0
- **Room:** 12 ft × 14 ft = 168 ft² ≈ 15.61 m²
- **Clear-height concept:** 10 ft
- **Generator:** 5 kW rated biogas spark-ignition genset
- **Electrical output:** 230 V, 50 Hz, single phase concept
- **Normal operating output:** ~4 kW
- **Gas demand at 4 kW:** ~2.23 m³/h
- **Gas demand at 5 kW:** ~2.79 m³/h
- **Daily runtime:** ~3.6–4.1 h/day
- **Gross daily generation:** ~14.5–16.4 kWh/day
- **Rated current:** ~21.7 A
- **Normal 4 kW current:** ~17.4 A
- **Concept generator breaker:** 32 A 2P
- **Concept ATS:** industrial interlocked 40–63 A 2P
- **Concept generator feeder:** 6 mm² copper for a short run, final engineer check required
- **Room ventilation:** ~1,500–2,000 m³/h concept
- **Generator power destination:** Essential Load Board only

## Energy topology
Normal source → Essential Load Board  
Biogas generator → ATS → Essential Load Board

Generator is isolated from the grid and from uncontrolled solar paralleling.

## Document map
| File | Purpose |
|---|---|
| [ARCHITECTURE.md](ARCHITECTURE.md) | generator-room form, access, ventilation and equipment zoning |
| [BLUEPRINT.md](BLUEPRINT.md) | exact local XYZ layout, genset, panels, louvers and exhaust |
| [DESIGN.md](DESIGN.md) | functional/mechanical/electrical design philosophy |
| [CALCULATIONS.md](CALCULATIONS.md) | gas, runtime, current, cable, ventilation, heat and cost math |
| [LOAD-SCHEDULE.md](LOAD-SCHEDULE.md) | critical, sequenced and shed loads |
| [SINGLE-LINE.md](SINGLE-LINE.md) | generator/ATS/essential-bus electrical single line |
| [POWER-ARCHITECTURE.md](POWER-ARCHITECTURE.md) | grid/solar/generator operating modes |
| [GAS-INTERFACE.md](GAS-INTERFACE.md) | Section 10 treated-gas train into engine |
| [VENTILATION-EXHAUST.md](VENTILATION-EXHAUST.md) | cooling air, combustion air, exhaust and room heat |
| [UTILITIES.md](UTILITIES.md) | gas, electrical, drainage, data, battery and earthing |
| [PROCESS.md](PROCESS.md) | start, transfer, run, stop and fault sequences |
| [EQUIPMENT.md](EQUIPMENT.md) | genset, ATS, panels, sensors, ventilation and safety equipment |
| [AUTOMATION.md](AUTOMATION.md) | PLC/genset/ATS interlocks and staged loads |
| [SAFETY.md](SAFETY.md) | gas, CO, exhaust, electricity, fire and lockout |
| [DIAGRAMS.md](DIAGRAMS.md) | room, power, gas and control diagrams |
| [CONSTRUCTION.md](CONSTRUCTION.md) | civil/mechanical/electrical installation and commissioning |
| [OPERATIONS-MAINTENANCE.md](OPERATIONS-MAINTENANCE.md) | inspection, oil/service, battery, ATS and ventilation maintenance |
| [BENEFITS.md](BENEFITS.md) | energy recovery, resilience and monitoring benefits |
| [COST.md](COST.md) | Bangladesh 2026 low/base/high planning budget |
| [IMAGE.md](IMAGE.md) | canonical visual geometry, prompts and QA |
| [images/README.md](images/README.md) | image naming |
| [images/IMAGE-GUIDE.md](images/IMAGE-GUIDE.md) | detailed image instructions |
| [images/VIEW-MATRIX.md](images/VIEW-MATRIX.md) | required room/equipment/diagram views |

## Public price context
Current Bangladesh October 2026 listings show ordinary 5 kW petrol/diesel generator prices roughly from Tk61,500 to Tk120,000 and a 5 kW gasoline/gas-type set around Tk75,000. These are not biogas-ready EPC packages and are used only as lower market benchmarks.
