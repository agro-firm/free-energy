# Gas Treatment — Canonical IMAGE.md

## Fixed geometry
- zone 10 ft long ×8 ft wide
- west inlet from Section 09
- east treated outlet to Section 11
- 2 ft inlet/KO band
- 4 ft twin H₂S bed band
- 4 ft polishing/meter/booster band
- open-sided weather canopy
- two vertical ~300 mm diameter H₂S vessels

## Required process order
KO → H₂S Lead → H₂S Lag → moisture separator → particulate filter → gas meter → booster/regulator → generator.

## Coordinate system
X0–10 ft west→east
Y0–8 ft south→north
Z vertical

## Required visible components
- KO pot
- twin H₂S vessels
- media labels
- crossover manifold
- sample ports
- coalescer
- filter
- H₂S monitor
- gas meter
- low-pressure booster
- regulator
- inlet/outlet pressure
- condensate closed drain
- gas detector
- bonding
- PLC panel outside classified zone

## Image math
```
gas design flow=3 m³/h
H₂S base=2000 ppm
H₂S raw≈25.6 g/day at 9.18 m³/day
25 kg bed theoretical capacity≈2.5 kg H₂S at 0.10 kg/kg
EBCT≈60 s at 3 m³/h
```

## Utility colors
raw gas dark green
treated gas light green
H₂S media orange
condensate cyan-grey
safety red
data dark blue
electrical purple

## Never show
- untreated bypass to generator
- water-treatment activated carbon bag dumped loosely
- open condensate bucket
- sealed unventilated shed
- ordinary fan/blower not gas-rated
- missing gas detector
- generator inside treatment skid
- H₂S vessel opened while live

## Required image categories
top plan, all sides, four aerials, full process skid, H₂S vessel cutaway, media bed, lead/lag swap, KO/coalescer, filter, gas meter, booster, H₂S analyzer, sample ports, P&ID, automation, media change, condensate drain, Section09→10→11 context.

## QA
Reject if treatment order, twin-bed concept, bypass rule, gas direction or moisture handling contradicts canonical documents.
