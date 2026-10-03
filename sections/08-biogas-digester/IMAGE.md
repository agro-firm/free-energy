# Biogas Digester — Canonical IMAGE.md

## Fixed geometry
- compound 20 ft long ×16 ft wide
- cylindrical semi-buried RCC digester
- internal diameter 2.8 m
- external planning diameter ~3.2 m
- total internal height ~4.06 m
- bottom ~3.0 m below grade
- normal liquid level ~0.25 m above grade
- gas-space internal top ~1.06 m above grade
- 20 m³ liquid +5 m³ headspace =25 m³ total
- center around X=10 ft, Y=7.5 ft

## Required visible interfaces
west: Section 07 feed
east: digestate overflow to Section 12
north: gas/PV safety to Section 09
south: maintenance access

## Utility colors
slurry brown
digestate yellow-brown
raw gas green
condensate cyan/grey
recirculation purple
P/V safety red
controls dark blue

## Required image categories
- top compound plan
- south/north/east/west
- four aerial corners
- full vertical cutaway
- 20 m³ liquid/5 m³ gas-volume infographic
- buried-depth section
- feed inlet detail
- digestate outlet chamber
- gas outlet/condensate
- P/V safety
- recirculation loop
- manway
- groundwater/uplift concept
- P&ID overlay
- startup/biology infographic
- Section07→08→09/12 context

## Never show
- vessel as high-pressure LPG tank
- open uncovered liquid
- person inside digester
- flame near gas outlet
- gas storage omitted/replaced by digester headspace
- incorrect 25 m³ liquid volume
- Section 09 gas holder inside the 16×20 ft compound
- unsafe sealed vent/relief line

## QA math
```
D=2.8 m
A≈6.1575 m²
Htotal≈4.06 m
Hliquid≈3.248 m
Hgas≈0.812 m
20+5=25 m³
```

Reject any image that changes these canonical planning dimensions unless a formal redesign is approved.
