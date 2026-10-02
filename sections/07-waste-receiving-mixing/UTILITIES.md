# Waste Receiving + Mixing — Utilities

## Water
Section 13 supplies dilution/cleaning water.

Design daily dosing:
```
~270 L/day
```

Line concept:
- 25 mm / 1-inch
- manual isolation
- strainer
- solenoid valve
- water flow meter/transmitter
- non-return protection as required

## Slurry piping
Concept:
- 75 mm / 3-inch-class pumped slurry lines
- long-radius bends
- minimal high points
- full-port isolation valves
- non-return valve on digester feed
- cleanout/flush tees
- unions/flanges for pump removal

Final diameter depends on rheology, solids, pump curve and distance.

## Gravity/overflow
Emergency/gravity containment line:
- 100 mm / 4-inch-class concept
- gravity only to contained ES-101
- never to stormwater

## Dirty drainage
All washdown/manure water:
```
floor → covered dirty drain → RS-101/ES-101
```

Roof water remains separate.

## Electrical
Concept loads:
- P-101 receiving pump ~0.75 kW
- M-101 mixer ~0.75 kW
- P-102 digester feed pump ~0.75 kW
- PLC/sensors/actuators
- one or two LED lights
- optional ventilation fan

Provide:
- local isolators
- motor overload
- earth-leakage protection where appropriate
- emergency stop
- IP-rated panel
- cable routing above splash zone

## Data/controls
Signals:
- RS-101 low/high/high-high
- ES-101 high/high-high
- MT-101 load cells
- water flow/total
- mixer run/fault
- P-101 run/fault
- P-102 run/fault
- slurry flow/total
- valve feedback
- Section 08 digester-ready/high-level inhibit
- optional H₂S/CH₄ sensor

## Ventilation
Semi-open architecture is primary.
Optional extraction only if risk assessment requires; electrical equipment must be appropriate to environment.

## Gas
No biogas process pipe should intentionally originate/terminate here. However manure can emit methane/H₂S, so stagnant covered sumps must be vented and the area kept ventilated.

## Communications
PLC should send:
- batch totals
- daily slurry total
- water ratio
- faults
- emergency-sump status
to the farm monitoring system.
