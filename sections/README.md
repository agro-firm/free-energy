# Plant Sections

This folder contains the physical and operational sections of the current compact plant.

## Current section count: 15

| No. | Section | Baseline |
|---:|---|---|
| 01 | Cow shed | 26 × 48 ft |
| 02 | Cow yard | 18 × 28 ft |
| 03 | Milk room + chiller | 14 × 18 ft |
| 04 | Office + vet + biosecurity | 12 × 15 ft |
| 05 | Feed store | 18 × 20 ft |
| 06 | Feed unloading canopy | 10 × 18 ft |
| 07 | Waste receiving + mixing | ~140 ft² |
| 08 | Biogas digester | 25 m³ in 16 × 20 ft compound |
| 09 | Gas storage | 8 m³ in 10 × 12 ft zone |
| 10 | Gas treatment | 8 × 10 ft |
| 11 | Generator + electrical | 12 × 14 ft, 5 kW generator |
| 12 | Fertilizer processing | 16 × 22 ft |
| 13 | Water utility | 8 × 12 ft |
| 14 | Truck/service lane | 14 ft wide |
| 15 | Rooftop solar | 15 kWp on cow-shed roof |

## Documentation standard

All detailed section work follows:
- [DOCUMENTATION-STANDARD.md](DOCUMENTATION-STANDARD.md)
- [WORK-STATUS.md](WORK-STATUS.md)

Each detailed section should contain:
- architecture
- blueprint
- design
- calculations
- utilities
- process
- equipment
- diagrams
- construction
- operations/maintenance
- benefits
- cost
- AI image guide
- image view matrix

## How to use this folder

Each section starts with:
- `README.md` — section purpose, baseline, interfaces and file index.
- `images/` — image instructions and generated visual library.

The engineering source of truth remains:
- `agent/skill/00-master-plant/SKILL.md`
- `agent/skill/01-engineering-math/SKILL.md`

If a section changes permanently, update:
1. that section's calculation/blueprint files,
2. its relevant skill,
3. the section README,
4. the master plant if a canonical baseline value changed,
5. affected image instructions.
