# Gas Storage — Blueprint and XYZ Specification

## Local coordinates
- origin southwest
- X=0–12 ft west→east
- Y=0–10 ft south→north
- Z=vertical

## Holder frame
Planning:
- X≈1.0–8.9 ft
- Y≈1.0–8.9 ft
- envelope ≈2.4×2.4 m / 7.87×7.87 ft
- top ≈2.4 m / 7.87 ft above slab

## Flexible membrane
Planning maximum inflated equivalent envelope:
- 2.0×2.0×2.0 m
- located centrally in protective frame
- membrane actual curved shape VENDOR

## Manifold/service strip
East side:
```
X≈9–12 ft
Y≈0–10 ft
```

Contains:
- inlet/outlet valves/manifold
- pressure transmitter
- membrane level sensor control
- gas detector
- condensate pot
- P/V protection interface
- PLC I/O enclosure placed outside classified area as required

## Gas inlet
From Section 08:
- enters west/southwest manifold
- DN40 / 1.5-inch class concept
- upstream primary condensate protection
- isolation valve
- secondary low-point condensate pot where needed
- non-return arrangement only if vendor/system design requires it

## Gas outlet
To Section 10:
- DN40 / 1.5-inch class concept
- full-port isolation
- flexible connector/strain relief as required
- treatment/booster occurs downstream in Section 10

## P/V protection
Independent low-pressure safety connection:
- cannot be disabled by normal PLC
- relief/vent path routed to safe location/flare manifold
- final pipe size/setpoints ENGINEER/VENDOR

## Level sensing
LIT-301:
- vendor membrane-position sensor
- ultrasonic/rope/linear sensing depending holder design
- reports 0–100% nominal volume

## Pressure
PIT-301:
- very-low-range transmitter
- normal operating pressure and high/low alarm values follow vendor

## Gas detector
GD-301:
- CH₄/H₂S detection after hazard review
- mounted according to sensor/gas behavior and ventilation study

## Bonding/lightning
- frame bonded to site earth
- gas piping bonded
- lightning protection per risk assessment
- membrane material anti-static/fire performance vendor verified

## Floor/drainage
No open water drain under gas bag.
Stormwater kept outside slab.
Condensate drains into closed dirty-process container/line, never stormwater.

## Drawing colors
raw gas green
condensate cyan-grey
P/V safety red
electrical/data dark blue
level/volume purple
earth/lightning yellow-green
