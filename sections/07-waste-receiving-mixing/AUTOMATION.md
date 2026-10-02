# Waste Receiving + Mixing — Automation and PLC Logic

## Modes
- OFF
- MANUAL
- AUTO
- MAINTENANCE/LOCKOUT

## Auto state machine
### S0 — Idle
Wait for feed window and minimum RS-101 material.

### S1 — Precheck
Require:
- no E-stop
- no critical alarm
- ES-101 not high-high
- MT-101 available
- digester communications healthy

### S2 — Load dung
- tare WIT-101
- start P-101
- target +67.5 kg manure mass
- stop on target or timeout

### S3 — Dose water
- open XV-201
- target 67.5 L via FIT-201
- close on target or timeout

### S4 — Mix
- start M-101
- planning 5–10 min
- stop on overload or abnormal vibration/current

### S5 — Digester permissive
Require Section 08:
- ready
- not high/high-high
- feed valve/path available

### S6 — Feed
- start P-102
- integrate FIT-301
- target ~0.135 m³
- stop on target, low MT-101, no-flow or high pressure/current

### S7 — Verify
Compare:
- starting MT mass
- ending MT mass
- FIT-301 volume
- expected batch

Raise deviation alarm if outside configurable tolerance.

### S8 — Log
Store:
- date/time
- manure kg
- water L
- slurry m³
- mix time
- feed time
- alarms
- pump runtime

Return S0.

## Key interlocks
- P-101 cannot run if MT-101 high/high mass
- M-101 cannot run dry
- P-102 cannot run without digester permissive
- XV-201 closes on power loss
- RS-101 HH triggers emergency logic
- ES-101 HH triggers critical stop/alarm
- no-flow while pump running trips sequence
- motor overload trips relevant motor

## Alarm priorities
### Critical
- emergency sump HH
- uncontrolled overflow
- E-stop
- digester high-high with full upstream storage

### High
- receiving sump HH
- feed pump fail
- flow meter fail
- mixer fail
- water-dosing failure

### Advisory
- batch deviation
- sensor maintenance
- high runtime
- screen cleaning due

## Manual fallback
Manual operation must require operator acknowledgement and retain physical containment/high-level protection. Timer-only slurry dosing is not the normal fallback.

## Data KPIs
- kg dung collected/day
- L dilution/day
- water:dung ratio
- m³ slurry/day
- batch deviation %
- kWh/day
- pump runtime
- blockage count
- emergency sump events
