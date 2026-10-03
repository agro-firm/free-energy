---
name: generator-electrical
description: Size and integrate the biogas generator, ATS, electrical panel and farm loads.
---

# Generator + Electrical Skill

## Canonical baseline
- Room: 12 × 14 ft.
- Generator: 5 kW rated.
- Supply concept: 230 V, 50 Hz, single phase.
- Normal operating target: ~4 kW.
- Gas demand at 4 kW: ~2.23 m³/h.
- Runtime at baseline gas: ~3.6–4.1 h/day.
- Generator supplies a dedicated Essential Load Board through an interlocked ATS/changeover.
- No grid backfeed.
- No solar/generator parallel operation unless explicitly approved later.

## Electrical
- Rated current: 5,000/230 ≈ 21.7 A.
- Normal 4 kW current: ≈17.4 A.
- Generator breaker concept: 32 A, 2-pole.
- ATS: 40 A minimum functional capacity; 63 A standard industrial size acceptable with correct upstream/downstream protection.
- Feeder concept: 6 mm² copper for short runs, subject to final ampacity/voltage-drop/fault/derating checks.
- Meter generator kWh, voltage, current, frequency and runtime.

## Load philosophy
Tier 1 critical loads always have priority.
Tier 2 loads are sequenced.
Tier 3/noncritical loads are locked out on generator power.

A 5 kW water heater, heavy feed mixer, multiple scraper motors and other high-demand loads must not run automatically on the biogas generator.

## Room
- Mechanical ventilation target: ~1,500–2,000 m³/h concept.
- Low-level cool-air intake; high-level hot-air exhaust.
- Engine exhaust via flexible connector, muffler and insulated pipe to outdoors.
- Gas detection, CO detection, emergency stop and fire response.
- Antivibration foundation/mounts.
- Battery/electric start.

## Integration
Start only with:
- Section 09 gas above required level,
- Section 10 treated-gas ready,
- no gas alarm,
- generator healthy,
- essential bus transfer available.

## Rule
Generator capacity follows available gas and essential-load strategy, not the room size.
