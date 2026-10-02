---
name: controls-automation
description: PLC/control philosophy for manure transfer, digester feed, gas storage, treatment and generator operation.
---

# Controls + Automation Skill

## Sequence
1. Scheduled scraper cycle.
2. Sump level confirmation.
3. Mixing and dilution.
4. Metered digester feed.
5. Gas-holder level and pressure monitoring.
6. Gas-treatment permissive.
7. Automatic generator start/stop.
8. Digestate handling alarms.
9. Water/utility alarms.

## Generator concept
Start only when gas level, pressure, treatment and generator-ready conditions are all valid.
Stop on low gas, gas alarm, treatment fault, engine/electrical fault or emergency stop.

## Data logging
Dung batches, slurry volume, digester feed, gas production, gas consumption, generator kWh, solar kWh, water, milk, fertilizer batches, alarms and runtime.

## Rule
Software interlocks never replace mechanical pressure relief, isolation or other physical safety devices.