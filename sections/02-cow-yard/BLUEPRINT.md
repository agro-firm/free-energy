# Cow Yard — Blueprint and XYZ Specification

## Local coordinate system
- origin (0,0,0): southwest yard corner
- X: west→east, 0–28 ft
- Y: south→north, 0–18 ft
- Z: vertical

## Plan zones
| X range | Width | Function |
|---|---:|---|
| 0–12 ft | 12 ft | shaded active zone |
| 12–24 ft | 12 ft | open active zone |
| 24–28 ft | 4 ft | water/service/drain strip |

Across Y, the full usable width is 18 ft.

## Area check
```
12×18 + 12×18 + 4×18
= 216 + 216 + 72
= 504 ft²
```
PASS.

## Shed gate concept
Assume local west boundary contains an approximately 8 ft cattle gate centered around:
```
X = 0
Y = 5 to 13 ft
```
Final global orientation is pending the site coordinate master.

## Service gate
Concept 4 ft gate on east/south service side. Final position depends on global plan.

## Drain
Linear dirty drain along east edge:
```
X ≈ 27.5–28 ft
Y = 0–18 ft
```
Concept length = 18 ft.

## Trough
Planning position within service strip:
```
X ≈ 24.5–27 ft
Y ≈ 11–17 ft
```
Actual vendor footprint controls final coordinates.

## Shade canopy
```
X = 0–12 ft
Y = 0–18 ft
```
Canopy posts must be kept outside primary cow circulation where possible.

## Floor slope concept
Primary fall west→east:
- planning slope = 1.25%
- run = 28 ft

```
fall = 28 × 0.0125
= 0.35 ft
= 4.2 in
≈ 106.7 mm
```

This is an ASSUMPTION; final drainage and animal-safety review may revise it.

## Z concept
- yard finished floor high side: Z = 0.00 datum
- east drain invert: determined from final civil design
- fence top: ~5 ft ASSUMPTION
- canopy low side: ~9.5–10 ft ASSUMPTION
- canopy high side: ~11 ft ASSUMPTION

## Drawing layers
- black = boundary/fence
- grey = pavement
- cyan = water
- brown/orange = dirty runoff
- light blue = clean canopy stormwater
- dark blue = electrical/data
- red = gates/safety
- green gas = **not applicable / absent**
