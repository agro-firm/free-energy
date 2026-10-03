# Generator + Electrical — Functional Design

## 1. Generator role
The generator converts stored/treated biogas into electricity when enough gas is available and/or emergency backup is required.

It is not designed to run 24/7.

## 2. Operating point
Rated:
```
5 kW
```

Normal target:
```
~4 kW
```

This keeps the engine near 80% load and avoids oversizing relative to fuel supply.

## 3. Electrical topology
Generator serves a dedicated Essential Load Board through ATS/changeover.

The generator does not energize the whole farm automatically.

## 4. Grid/solar relationship
Normal farm operation:
- grid/solar serve main bus
- essential bus is fed from normal source

Biogas generation:
- generator starts isolated
- stabilizes
- ATS transfers Essential Load Board to generator
- nonessential main-bus loads remain off generator

No parallel operation with grid.

Solar/generator parallel operation is prohibited until Section 15 final inverter architecture explicitly supports it.

## 5. Load shedding
Tier 1:
- milk chiller
- vaccine refrigerator/ICT
- gas treatment controls/booster
- essential PLC/data
- emergency lighting

Tier 2:
- water pump
- one or limited cow-shed fan
- milk transfer pump
- selected process pump

Tier 3:
- hot-water heater
- feed mixer
- multiple scraper drives
- dehumidifiers
- convenience loads

## 6. Start philosophy
Gas-rich normal cycle:
- holder ≥75%
- Section 10 treated gas ready
- generator healthy
- start unloaded
- verify 230 V / 50 Hz
- transfer essential bus
- stage loads

Emergency grid failure:
- may start at lower gas threshold (~30% planning) if critical power is required and gas quality is ready
- stop at holder low cutout

## 7. Stop philosophy
- remove high/temporary loads
- transfer essential bus back to normal source
- run vendor cool-down
- close gas solenoid
- stop engine
- log gas/kWh/runtime

## 8. Gas train
Local room gas train is only final engine isolation/control; Section 10 already performs treatment, metering and pressure conditioning.

## 9. Maintenance philosophy
Keep service items accessible:
- oil
- plug/ignition
- air filter
- alternator
- starter battery
- valves
- panels
- exhaust flex/muffler
