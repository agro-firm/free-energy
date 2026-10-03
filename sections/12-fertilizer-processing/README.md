# 12 — Fertilizer Processing

## Documentation status
**Detailed digestate-separation / fertilizer-processing concept package — Section 12 complete for planning.**

## Canonical baseline
- **Plant version:** PLANT-V1.0
- **Footprint:** 16 ft × 22 ft = 352 ft² ≈ 32.70 m²
- **Digestate input:** ~0.54 m³/day
- **Buffer tank:** ~0.75 m³ gross / ~0.60 m³ working
- **Separator:** ~500 kg/h screw press concept
- **Separator run time:** ~1.08 h/day at 540 kg/day
- **Base captured dry solids:** ~25.14 kg/day
- **Base wet cake:** ~83.8 kg/day at 30% TS
- **Base finished product:** ~38.7 kg/day at 65% TS ≈14.1 t/year
- **Liquid output:** ~0.456 m³/day base planning
- **Liquid tank:** ~2.0 m³ covered, ~4.4 days storage
- **Bag size:** 25 kg concept
- **Service-lane dispatch:** direct access
- **Commercial-sale status:** only after current DAE/MoA compliance, lab analysis and required registration/approval

## Section zones
| Zone | Size | Area |
|---|---:|---:|
| Digestate receiving + screw press | 6 × 16 ft | 96 ft² |
| Curing / drying | 8 × 16 ft | 128 ft² |
| Bagging + finished product | 4 × 16 ft | 64 ft² |
| Liquid tank + service | 4 × 16 ft | 64 ft² |
| **Total** | | **352 ft²** |

## Document map
| File | Purpose |
|---|---|
| [ARCHITECTURE.md](ARCHITECTURE.md) | covered process architecture, drying/curing and loading relationships |
| [BLUEPRINT.md](BLUEPRINT.md) | exact X/Y/Z zones, tanks, press, beds and dispatch |
| [DESIGN.md](DESIGN.md) | solids/liquid handling, curing, bagging and product workflow |
| [CALCULATIONS.md](CALCULATIONS.md) | digestate, capture, cake, tank, run time, bag and cost math |
| [SOLIDS-BALANCE.md](SOLIDS-BALANCE.md) | 50/70/90% capture scenarios and product-yield sensitivity |
| [LIQUID-DIGESTATE.md](LIQUID-DIGESTATE.md) | liquid tank sizing, testing, storage and field-use logic |
| [QUALITY-REGULATORY.md](QUALITY-REGULATORY.md) | lab tests, farm-use vs commercial product and Bangladesh compliance |
| [UTILITIES.md](UTILITIES.md) | digestate piping, water, drains, power, ventilation and stormwater |
| [PROCESS.md](PROCESS.md) | receive, separate, cure, dry, screen, bag and dispatch sequence |
| [EQUIPMENT.md](EQUIPMENT.md) | tanks, screw press, pump, beds, scales and bagging equipment |
| [P&ID.md](P&ID.md) | liquid/solid process and instrumentation concept |
| [AUTOMATION.md](AUTOMATION.md) | buffer/press/tank interlocks and alarms |
| [SAFETY.md](SAFETY.md) | biological, mechanical, slips, tank entry and media handling risks |
| [DIAGRAMS.md](DIAGRAMS.md) | plan, process, mass-balance and drainage diagrams |
| [CONSTRUCTION.md](CONSTRUCTION.md) | civil, drains, roof, equipment and commissioning |
| [OPERATIONS-MAINTENANCE.md](OPERATIONS-MAINTENANCE.md) | daily/weekly/monthly operation and maintenance |
| [BENEFITS.md](BENEFITS.md) | nutrient recovery, volume reduction and business value |
| [COST.md](COST.md) | Bangladesh 2026 low/base/high planning cost model |
| [IMAGE.md](IMAGE.md) | canonical image math, prompts and QA |
| [images/README.md](images/README.md) | image naming/governance |
| [images/IMAGE-GUIDE.md](images/IMAGE-GUIDE.md) | detailed camera/rendering instructions |
| [images/VIEW-MATRIX.md](images/VIEW-MATRIX.md) | required process/detail views |

## Compliance note
Bangladesh DAE/MoA maintains fertilizer production/distribution registration services and publishes approved organic-fertilizer specifications. A 2025 preliminary draft Fertilizer Management Act explicitly defines organic fertilizer, but the draft itself must not be treated as the final governing law. Verify the current effective law and DAE requirements before commercial sale.
