# Biogas Digester — Automation and Controls

## Modes
- NORMAL/AUTO
- HOLD FEED
- MAINTENANCE
- EMERGENCY

## Feed permissive to Section 07
TRUE only when:
- liquid level normal
- no high-high level
- gas pressure below high inhibit
- digestate outlet available
- no maintenance lockout
- no critical gas alarm

## Recirculation
Planning cycle:
- short periodic run
- start only if liquid level sufficient
- stop on motor overload/no-flow
- avoid running during conditions that cause foaming

Final schedule is tuned operationally.

## Alarms
### Critical
- gas pressure high-high
- liquid level high-high
- gas detector high
- outlet failure with continuing inflow
- emergency stop

### High
- high liquid level
- high gas pressure
- low/high temperature
- recirculation pump fail
- outlet chamber high

### Advisory
- pH trend outside target
- lower gas production
- high pump runtime
- instrument maintenance due

## Hard safety
P/V relief is mechanical and independent of PLC.
No software command may disable required pressure/vacuum protection.

## Data logging
Daily:
- slurry in m³
- digestate out estimate
- temperature
- pH
- gas m³
- gas pressure
- recirculation runtime
- alarms

## Performance dashboard
Calculate:
- m³ gas/m³ slurry
- m³ gas/kg dung
- kWh electricity equivalent
- 7-day/30-day gas trend
- pH/temperature trend
