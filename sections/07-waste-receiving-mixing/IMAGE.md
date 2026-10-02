# Waste Receiving + Mixing — Canonical IMAGE.md

## Fixed geometry
- Section footprint 14 ft long × 10 ft wide
- inlet/receiving 4×10 ft west
- mixing/process 6×10 ft center
- control/emergency 4×10 ft east
- semi-open covered dirty-process bay
- RS-101 covered sump
- MT-101 500 L mixing tank on load cells
- ES-101 emergency sump
- direct west manure inlet
- direct east/northeast digester feed

## Image math
```
14×10 = 140 ft²
RS-101 gross ≈0.765 m³
MT-101 gross =0.50 m³
ES-101 gross ≈1.04 m³
batch =67.5 kg dung+67.5 L water≈0.135 m³
4 batches/day≈0.54 m³/day
```

## Coordinate system
X0–14 west→east
Y0–10 south→north
Z vertical
sumps extend to Z≈-3 ft
roof around Z≈10–11 ft concept

## Required visible equipment
- cow-shed inlet channel
- coarse screen
- grit pocket
- covered receiving sump
- P-101
- mixing tank/load cells
- mixer
- water meter/solenoid
- P-102
- electromagnetic flow meter
- valves/check valve
- emergency sump
- PLC panel
- level sensors
- dirty drains
- venting
- safety signs

## Utility colors
manure/slurry brown
water cyan
emergency orange
power/data dark blue
control purple
vent grey

## Never show
- open unguarded deep pit
- worker standing inside sump
- clean milk/feed traffic
- process overflow to storm drain
- gas holder/generator inside Section 07
- random open flames
- manure pump with tiny garden hose
- image changing tank capacities

## Required image types
top orthographic, west inlet, east digester-feed side, all aerial corners, screen detail, sump cutaway, load-cell mixing tank, pump/valve skid, flow-meter detail, emergency-sump view, PLC/HMI view, P&ID overlay, automatic batch sequence, dirty drainage, water dosing, maintenance/removal path and night/monsoon variants.

## QA
Reject if process order, tank sizes, containment, pipe direction or automation logic contradicts BLUEPRINT.md/P&ID.md.
