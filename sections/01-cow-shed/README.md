# 01 — Cow Shed

## Documentation status
**Detailed engineering concept package — Section 01 complete for planning.**

This folder is the section-level source for the 20-cow shed. It does not replace structural, electrical, plumbing, livestock-welfare, fire, or local permit drawings prepared by qualified professionals.

## Canonical baseline
- **Plant version:** PLANT-V1.0
- **Section footprint:** 26 ft × 48 ft
- **Area:** 1,248 ft² ≈ 115.94 m²
- **Capacity:** 20 adult cows
- **Layout concept:** 2 rows × 10 cows
- **Roof use:** 15 kWp project solar target is mounted on this roof; final panel layout belongs to Section 15.
- **Primary outputs:** milk to Section 03; manure to Section 07.
- **Primary inputs:** feed from Section 05, water from Section 13, electricity from Section 11 / Section 15.

## Section document map

| File | Purpose |
|---|---|
| [ARCHITECTURE.md](ARCHITECTURE.md) | Architectural concept, geometry, roof, ventilation, materials, space planning |
| [BLUEPRINT.md](BLUEPRINT.md) | Local X/Y/Z coordinate system, internal zoning, dimension schedule and plan logic |
| [DESIGN.md](DESIGN.md) | Functional/interior design, animal handling, finishes, human workflow and design intent |
| [CALCULATIONS.md](CALCULATIONS.md) | Math-solver style calculations and dimensional checks |
| [UTILITIES.md](UTILITIES.md) | Water, drainage, electrical, data/sensors and explicit gas-line exclusion |
| [PROCESS.md](PROCESS.md) | Daily operating workflow and interfaces with milk, feed and manure systems |
| [EQUIPMENT.md](EQUIPMENT.md) | Equipment and fixture schedule with FIXED/ASSUMPTION/VENDOR tags |
| [DIAGRAMS.md](DIAGRAMS.md) | Mermaid and ASCII diagrams for plan, flow and utility concepts |
| [CONSTRUCTION.md](CONSTRUCTION.md) | Construction sequence, materials, hold points and quality checks |
| [OPERATIONS-MAINTENANCE.md](OPERATIONS-MAINTENANCE.md) | Cleaning, inspection, maintenance and operating checks |
| [BENEFITS.md](BENEFITS.md) | Functional, hygiene, labor, energy and integration benefits |
| [COST.md](COST.md) | 2026 Bangladesh planning cost model with low/base/high ranges |
| [IMAGE.md](IMAGE.md) | Canonical image-generation rules, geometry math, prompts and QA |
| [images/README.md](images/README.md) | Image folder rules |
| [images/IMAGE-GUIDE.md](images/IMAGE-GUIDE.md) | AI image-generation specification for every side, angle and interior view |
| [images/VIEW-MATRIX.md](images/VIEW-MATRIX.md) | Camera coordinates and required view checklist |

## Internal design summary

The 26 ft shed width is organized conceptually as:

```text
3.0 ft dirty/service
5.5 ft cow stall
1.5 ft manger
6.0 ft central feed alley
1.5 ft manger
5.5 ft cow stall
3.0 ft dirty/service
= 26.0 ft
```

The 48 ft length uses:
- 4 ft cross/service zone at one end
- 10 stalls × 4 ft = 40 ft
- 4 ft cross/service zone at the opposite end

The local coordinate details are defined in [BLUEPRINT.md](BLUEPRINT.md).

## Mandatory interfaces

### Clean milk
Cow → sanitary milking connection → Section 03 milk room/chiller.

### Feed
Section 05 feed store → shed feed entrance → central feed alley → mangers.

### Manure
Cow rows → scraper/dirty lanes → downstream collection point → Section 07 waste receiving/mixing.

### Water
Section 13 → shed water header → troughs/wash points.

### Electricity
Section 11 / Section 15 → shed subpanel → lights/fans/scraper controls.

### Gas
**No raw or treated biogas pipe is to be routed through the cow shed.**

## Design hierarchy
Before changing this section, read:
1. `agent/skill/00-master-plant/SKILL.md`
2. `agent/skill/01-engineering-math/SKILL.md`
3. `agent/skill/02-site-layout/SKILL.md`
4. `agent/skill/03-cow-shed/SKILL.md`
5. `agent/skill/04-manure-automation/SKILL.md`
6. `agent/skill/08-solar/SKILL.md`
7. `agent/skill/12-water-drainage/SKILL.md`
8. `agent/skill/15-visualization-images/SKILL.md` for images

Any accepted dimension change must also pass `agent/skill/18-construction-review/SKILL.md`.
