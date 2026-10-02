# Waste Receiving + Mixing — Blueprint and XYZ Specification

## Local coordinate system
- origin = southwest floor corner
- X = 0–14 ft west→east
- Y = 0–10 ft south→north
- Z = vertical
- Section 01/cow-shed manure inlet approaches west side
- Section 08 digester feed line exits east/northeast side

## Plan zones
| Zone | X | Y | Size | Area |
|---|---|---|---|---:|
| Inlet/receiving | 0–4 | 0–10 | 4×10 | 40 ft² |
| Mixing/process | 4–10 | 0–10 | 6×10 | 60 ft² |
| Control/emergency | 10–14 | 0–10 | 4×10 | 40 ft² |

## Receiving sump RS-101
Concept internal:
```
3 ft × 3 ft × 3 ft deep
= 27 ft³
27 × 0.0283168 = 0.7646 m³ gross
```

Planning working volume:
```
≈0.60 m³
```

Location:
```
X≈0.5–3.5
Y≈3.5–6.5
```

## Coarse screen SC-101
At west inlet before RS-101:
- removable basket/bar screen
- catches rope, bedding, plastic, stones and large debris
- manually accessible from standing level

## Grit pocket GP-101
Small low pocket immediately upstream/within receiving inlet, removable by scoop/vacuum from above.

## Mixing tank MT-101
- gross = 0.50 m³ / 500 L
- working target ≈0.35 m³
- mounted on load-cell frame

Planning center:
```
X≈7
Y≈5
```

## Emergency sump ES-101
Concept:
```
3.5 ft × 3.5 ft × 3 ft
= 36.75 ft³
36.75 × 0.0283168
≈1.041 m³ gross
```

Planning working:
```
≈0.80 m³
```

Location:
```
X≈10.25–13.75
Y≈3.25–6.75
```

## Water line
Concept 25 mm / 1-inch:
- overhead/wall-mounted
- isolation valve
- strainer
- solenoid valve XV-201
- water flow meter FI-201
- discharge above MT-101

## Slurry lines
Planning:
- receiving pump discharge: 75 mm / 3-inch-class
- mixing tank feed/slurry line: 75 mm / 3-inch-class
- emergency/gravity overflow: 100 mm / 4-inch-class
- cleanout/flush points vendor/engineer selected

## Digester feed line
Exits Section 07 toward Section 08 through:
- P-102 feed pump
- non-return valve
- isolation valve
- electromagnetic flow meter FIT-301
- sample/cleanout point

## Elevation concept
- finished floor Z=0
- sump top/cover Z≈0
- sump bottoms Z≈-3 ft
- mixing tank base Z≈+1 ft frame
- tank top ~4–5 ft vendor
- electrical panel bottom ≥4 ft above floor/splash zone
- pipe rack ~6–8 ft where practical
- roof ~10–11 ft clear ASSUMPTION

## Dirty floor drainage
Floor slope 1.5% over typical 6 ft local run:
```
6 × 0.015 = 0.09 ft
= 1.08 in
```
toward covered dirty drain/sump, not stormwater.

## Drawing colors
manure/slurry brown
water cyan
emergency flow orange
electrical/data dark blue
controls purple
vent/odor grey
gas green = not a process gas line here
