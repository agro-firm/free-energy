# Feed Unloading Canopy — Blueprint and XYZ Specification

## Local coordinate system
- origin = southwest canopy corner at service-lane edge
- X = west→east, 0–18 ft
- Y = south→north, 0–10 ft
- Z = vertical
- Section 05 feed-store wall is immediately north of Y=10
- Section 14 service lane lies south of Y=0

## Canopy zones
| Zone | X | Y | Size | Area |
|---|---|---|---|---:|
| Fresh forage staging | 0–4 | 0–10 | 4×10 | 40 ft² |
| Main unloading | 4–14 | 0–10 | 10×10 | 100 ft² |
| Inspection/safety | 14–18 | 0–10 | 4×10 | 40 ft² |

Area:
```
40 + 100 + 40 = 180 ft²
```

## Roof plane
High line:
```
Y=10, Z≈14 ft
```

Low line:
```
Y=0, Z≈12 ft
```

## Column concept
Preferred conceptual columns:
- C1 (0,0)
- C2 (18,0)
- C3 (0,10)
- C4 (18,10)

This leaves the full 18-ft front opening clear. Actual structure may require additional framing; any added column must be checked against unloading movement.

## Feed-store door
Concept receiving door:
- centered north wall beyond canopy
- approximately X=5–13 ft
- 8 ft clear width ASSUMPTION
- flush/low threshold

## Service lane / truck envelope
Section 14 local extension:
```
Y = -14 to 0 ft
```

Concept truck:
- length along X: 20 ft
- width along Y: 8 ft
- center around X=9, Y=-8
- truck envelope approximately X=-1 to 19, Y=-12 to -4

This leaves:
- ~4 ft gap from truck north side to canopy edge
- ~2 ft lane clearance on truck south side

Actual truck geometry overrides this assumption.

## Floor slope
Canopy apron slopes south/outward:
```
1% × 10 ft = 0.10 ft
= 1.2 in
```

Outer trench drain along:
```
Y≈0, X=0–18
```

Trench longitudinal slope concept:
```
1% × 18 ft = 0.18 ft
= 2.16 in
```

## Fresh-forage stage
Planning max:
```
600 kg temporary
```
Zone:
```
40 ft² = 3.716 m²
```

Average loading:
```
600 / 3.716 = 161.5 kg/m²
```

## Pallet design check
Planning temporary pallet load:
```
1,000 kg
```

Assume pallet footprint:
```
1.2 m × 1.0 m = 1.2 m²
```

Average under pallet:
```
1,000 / 1.2 = 833 kg/m²
```

This is a planning load only; wheel/point loads govern structural slab design.

## Z concept
- apron finished floor Z=0
- high roof Z≈14 ft
- low roof Z≈12 ft
- lights around Z=10–11 ft
- gutter at low edge Z≈12 ft

## Drawing colors
- dry feed: amber
- fresh forage: green
- truck: grey
- pedestrian/safety: yellow
- roof stormwater: light blue
- apron drainage: brown
- electrical/data: dark blue
- gas: absent
