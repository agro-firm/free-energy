# 06 — Feed Unloading Canopy

## Documentation status
**Detailed engineering concept package — Section 06 complete for planning.**

## Canonical baseline
- **Plant version:** PLANT-V1.0
- **Footprint:** 10 ft × 18 ft
- **Area:** 180 ft² ≈ 16.72 m²
- **Function:** covered side-unloading/transfer apron between Section 14 service lane and Section 05 feed store
- **Truck location:** truck remains in the 14-ft service lane; the canopy covers the transfer apron, not the whole vehicle
- **Roof form:** single-slope lean-to canopy
- **Concept high side:** ~14 ft at feed-store side
- **Concept low side:** ~12 ft at lane side
- **Fresh forage staging:** up to ~300 kg/day normal; max ~600 kg / 2 days temporary staging
- **Dry-feed flow:** truck → canopy → Section 05 receiving/quarantine
- **Green-forage flow:** truck → canopy short-stage → same-day/next-day feed preparation → cows

## Space program
| Zone | Size | Area |
|---|---:|---:|
| Fresh-forage short staging | 4 × 10 ft | 40 ft² |
| Main bag/pallet unloading | 10 × 10 ft | 100 ft² |
| Inspection/trolley/safety zone | 4 × 10 ft | 40 ft² |
| **Total** | | **180 ft²** |

## Document map
| File | Purpose |
|---|---|
| [ARCHITECTURE.md](ARCHITECTURE.md) | canopy form, truck relationship, roof, structure and weather protection |
| [BLUEPRINT.md](BLUEPRINT.md) | exact XYZ coordinates, truck envelope, zones, columns and drainage |
| [DESIGN.md](DESIGN.md) | loading workflow, fresh-forage staging, worker safety and ergonomics |
| [CALCULATIONS.md](CALCULATIONS.md) | area, roof slope, truck clearance, loads, drainage and cost math |
| [UTILITIES.md](UTILITIES.md) | lighting, CCTV, roof stormwater, apron drainage and gas exclusion |
| [PROCESS.md](PROCESS.md) | truck arrival, securing, unloading, inspection, staging and dispatch |
| [EQUIPMENT.md](EQUIPMENT.md) | pallet truck, platform trolley, chocks, barriers, lights and safety |
| [DIAGRAMS.md](DIAGRAMS.md) | plan, truck/canopy relation, flow and drainage diagrams |
| [CONSTRUCTION.md](CONSTRUCTION.md) | canopy/apron build sequence, hold points and commissioning |
| [OPERATIONS-MAINTENANCE.md](OPERATIONS-MAINTENANCE.md) | daily loading, drainage, roof, trolley and safety checks |
| [BENEFITS.md](BENEFITS.md) | rain protection, labor, logistics, feed-quality and land-use benefits |
| [COST.md](COST.md) | 2026 Bangladesh low/base/high cost model |
| [IMAGE.md](IMAGE.md) | canonical image geometry, prompts and QA |
| [images/README.md](images/README.md) | image naming/governance |
| [images/IMAGE-GUIDE.md](images/IMAGE-GUIDE.md) | detailed rendering prompts and camera coordinates |
| [images/VIEW-MATRIX.md](images/VIEW-MATRIX.md) | all required unloading/loading views |

## Mandatory interfaces
- **South:** Section 14 service lane
- **North:** Section 05 feed store receiving door
- Section 06 must never block the service lane permanently
- no feed is stored here long term
- no manure, fertilizer, biogas or generator equipment belongs here
