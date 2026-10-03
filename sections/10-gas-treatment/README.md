# 10 — Gas Treatment

## Documentation status
**Detailed gas-cleanup/process-engineering concept package — Section 10 complete for planning.**

## Canonical baseline
- **Plant version:** PLANT-V1.0
- **Zone:** 8 ft × 10 ft = 80 ft² ≈ 7.43 m²
- **Gas source:** Section 09 raw-gas holder
- **Gas destination:** Section 11 generator
- **Design gas flow:** 3 m³/h peak concept
- **Typical operating generator demand:** ~2.23 m³/h
- **Raw H₂S sizing assumption:** 2,000 ppm
- **Sensitivity range:** 1,000–3,000 ppm
- **Planning outlet H₂S:** ≤100 ppm; preferred ≤50 ppm if generator manufacturer requires
- **Primary H₂S system:** two 25 kg media vessels in lead/lag series
- **Bulk moisture:** inlet knockout pot
- **Fine moisture:** coalescing separator; optional desiccant cartridge if generator dew-point requirement demands
- **Particulate polish:** final filter after media
- **Gas metering:** low-flow thermal/positive-displacement gas meter
- **Pressure:** low-pressure booster/regulator only as needed
- **No untreated bypass to generator**

## Canonical treatment sequence
Section 09 → knockout/condensate → H₂S Lead A → H₂S Lag B → fine moisture/coalescer → particulate filter → gas meter → booster/regulator → Section 11.

## Document map
| File | Purpose |
|---|---|
| [ARCHITECTURE.md](ARCHITECTURE.md) | skid shelter, vessel access, ventilation and service layout |
| [BLUEPRINT.md](BLUEPRINT.md) | exact XYZ equipment zones and pipe routing |
| [DESIGN.md](DESIGN.md) | treatment chemistry, moisture, filtration and pressure philosophy |
| [CALCULATIONS.md](CALCULATIONS.md) | H₂S mass, media life, EBCT, gas velocity, power and cost math |
| [UTILITIES.md](UTILITIES.md) | gas piping, condensate, drains, electrical/data and earthing |
| [PROCESS.md](PROCESS.md) | normal cleanup, lead/lag swap, startup, shutdown and failures |
| [GAS-QUALITY.md](GAS-QUALITY.md) | inlet/outlet gas specifications, sample points and acceptance |
| [MEDIA-MANAGEMENT.md](MEDIA-MANAGEMENT.md) | media loading, breakthrough, replacement and disposal |
| [EQUIPMENT.md](EQUIPMENT.md) | vessels, filters, meter, sensors, booster and control equipment |
| [P&ID.md](P&ID.md) | tagged process/instrumentation arrangement |
| [AUTOMATION.md](AUTOMATION.md) | treatment permissives, alarms and generator handoff |
| [SAFETY.md](SAFETY.md) | methane/H₂S, media change, pressure and hot-work controls |
| [DIAGRAMS.md](DIAGRAMS.md) | skid plan, process, lead/lag and control diagrams |
| [CONSTRUCTION.md](CONSTRUCTION.md) | skid installation, pressure/leak testing and commissioning |
| [OPERATIONS-MAINTENANCE.md](OPERATIONS-MAINTENANCE.md) | daily/weekly/monthly gas-quality and equipment maintenance |
| [BENEFITS.md](BENEFITS.md) | engine protection, gas recovery and operating benefits |
| [COST.md](COST.md) | Bangladesh 2026 low/base/high planning budget |
| [IMAGE.md](IMAGE.md) | canonical image geometry, prompts and QA |
| [images/README.md](images/README.md) | image naming/governance |
| [images/IMAGE-GUIDE.md](images/IMAGE-GUIDE.md) | detailed camera/prompt instructions |
| [images/VIEW-MATRIX.md](images/VIEW-MATRIX.md) | required views |

## Technical references
Oklahoma State University notes that raw biogas is generally saturated with water vapor and that H₂S plus water is corrosive; it lists activated carbon and iron oxide among H₂S removal methods:
https://extension.okstate.edu/fact-sheets/anaerobic-digestion-biogas-utilization-and-cleanup

A 2025 open-access Energy & Fuels review covers metal-oxide-modified activated carbon for biogas H₂S/CO₂ removal:
https://pubs.acs.org/doi/10.1021/acs.energyfuels.4c03493
