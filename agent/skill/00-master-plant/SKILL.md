---
name: master-plant
description: Canonical source of truth for the compact integrated dairy-energy plant.
---

# Master Plant Skill

## Approved baseline
- Plot: 65 ft × 95 ft = 6,175 ft² ≈ 573.7 m² ≈ 0.142 acre.
- Herd: 20 adult cows.
- Cow shed: 26 × 48 ft.
- Cow yard: 18 × 28 ft.
- Milk room + chiller: 14 × 18 ft.
- Office + vet + biosecurity: 12 × 15 ft.
- Feed store: 18 × 20 ft.
- Feed unloading canopy: 10 × 18 ft.
- Waste receiving/mixing: 10 × 14 ft = 140 ft².
- Digester compound: 16 × 20 ft; 25 m³ total digester; 20 m³ target working liquid volume.
- Raw gas storage: 8 m³ nominal low-pressure flexible membrane holder in a 10 × 12 ft zone.
- Gas treatment: 8 × 10 ft treatment skid.
- Generator + electrical: **12 × 14 ft room; 5 kW rated, 230 V, 50 Hz, single-phase biogas generator concept feeding a dedicated Essential Load Board through interlocked ATS/changeover**.
- Fertilizer processing: 16 × 22 ft.
- Water utility: 8 × 12 ft.
- Service lane: 14 ft wide.
- Rooftop solar: 15 kWp on cow-shed roof.

## Canonical energy architecture
Solar/grid normally serve the farm main bus. The 5 kW biogas generator serves an Essential Load Board through an interlocked transfer system. The generator does not backfeed or parallel the utility, and it does not parallel rooftop solar unless a future Section 15 inverter/genset design is explicitly approved by both vendors and the electrical engineer.

## Baseline calculations
- Biogas: 8.10–9.18 m³/day.
- Planning methane: ~60%.
- Electrical yield: ~1.79 kWh/m³ at 30% engine-generator efficiency.
- Gross generator energy: ~14.5–16.4 kWh/day.
- Generator rated output: 5 kW.
- Normal operating target: ~4 kW.
- Gas at 4 kW: ~2.23 m³/h.
- Runtime: ~3.6–4.1 h/day.
- Rated current at 230 V: ~21.7 A.
- Normal 4 kW current: ~17.4 A.
- Concept generator breaker: 32 A 2-pole.
- Concept generator feeder: 2C × 6 mm² copper + protective conductor, final sizing by engineer.
- Room ventilation planning target: ~1,500–2,000 m³/h, final vendor airflow governs.

## Non-negotiable rules
1. Untreated raw gas never bypasses Section 10 to the generator.
2. Generator never backfeeds the grid.
3. Generator/solar paralleling is prohibited unless explicitly engineered and vendor-approved.
4. Noncritical loads are shed before generator overload.
5. Exhaust gas is discharged outdoors, never into occupied/process spaces.
6. No image may change canonical dimensions or topology.
