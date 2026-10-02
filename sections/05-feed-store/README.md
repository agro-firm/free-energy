# 05 — Feed Store

## Documentation status
**Detailed engineering concept package — Section 05 complete for planning.**

## Canonical baseline
- **Plant version:** PLANT-V1.0
- **Footprint:** 18 ft × 20 ft
- **Area:** 360 ft² ≈ 33.45 m²
- **Clear-height concept:** 12 ft ASSUMPTION
- **Primary role:** short-duration dry feed, concentrate, mineral and ration-preparation storage
- **Inventory philosophy:** 3–7 days for concentrate/dry roughage; frequent fresh green-fodder delivery
- **Fresh green forage:** staged through Section 06, not long-term stored inside
- **Service-lane/unloading side:** south in local coordinates
- **Cow-shed dispatch side:** north in local coordinates

## Feed-design assumptions
- Total herd dry-matter basis: 20 cows × 12 kg DM/day = 240 kg DM/day
- Concentrate design quantity: 60 kg/day ASSUMPTION derived from existing budget and current 2026 market
- Dry roughage design quantity: 80 kg/day ASSUMPTION
- Mineral/salt/premix: 3 kg/day ASSUMPTION
- Fresh green forage: 300 kg/day as-fed ASSUMPTION, daily/1–2 day delivery outside long-term store

## Document map
| File | Purpose |
|---|---|
| [ARCHITECTURE.md](ARCHITECTURE.md) | dry-store architecture, roof, moisture control, pest/fire design |
| [BLUEPRINT.md](BLUEPRINT.md) | exact X/Y/Z zones, doors, racks, pallets, aisles and prep area |
| [DESIGN.md](DESIGN.md) | feed handling, FIFO/FEFO, storage interiors, dry-cleaning and ergonomics |
| [CALCULATIONS.md](CALCULATIONS.md) | feed quantities, bag/rack volume, density, ventilation, electrical and cost math |
| [UTILITIES.md](UTILITIES.md) | electrical, ventilation, humidity monitoring, minimal water/drainage and gas exclusion |
| [PROCESS.md](PROCESS.md) | receive, inspect, quarantine, store, pick, weigh, mix and dispatch |
| [EQUIPMENT.md](EQUIPMENT.md) | racks, pallets, scale, bins, hygrometer, dehumidifier and optional mixer |
| [DIAGRAMS.md](DIAGRAMS.md) | plan, material flow, inventory and utility diagrams |
| [CONSTRUCTION.md](CONSTRUCTION.md) | dry-floor, weatherproofing, pest-proofing, fire and commissioning plan |
| [OPERATIONS-MAINTENANCE.md](OPERATIONS-MAINTENANCE.md) | daily stock, pest, moisture, cleaning and maintenance |
| [BENEFITS.md](BENEFITS.md) | feed quality, waste reduction, labor and inventory benefits |
| [COST.md](COST.md) | 2026 Bangladesh low/base/high cost model |
| [IMAGE.md](IMAGE.md) | canonical image-generation geometry, prompts and QA |
| [images/README.md](images/README.md) | image naming/governance |
| [images/IMAGE-GUIDE.md](images/IMAGE-GUIDE.md) | detailed prompts and camera rules |
| [images/VIEW-MATRIX.md](images/VIEW-MATRIX.md) | all required views |

## Mandatory interfaces
- Section 06 unloading canopy → receiving/quarantine
- Section 05 storage → weighing/prep → north dispatch to Section 01 cow shed
- Section 13 provides only small clean-water service if needed
- no manure, milk, fertilizer, gas-storage or generator equipment inside
