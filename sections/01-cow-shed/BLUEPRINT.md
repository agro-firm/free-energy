# Cow Shed — Blueprint and Coordinate Specification

## 1. Purpose

This file defines a reproducible geometric blueprint for Section 01 so that CAD work, AI images, diagrams and future engineering documents describe the same shed.

It is a **planning blueprint**, not a permit/construction drawing.

## 2. Local coordinate system

Use a section-local right-handed coordinate system:

- **Origin (0,0,0):** southwest floor corner of the 26 × 48 ft shed
- **X axis:** along the 48 ft shed length, west → east
- **Y axis:** across the 26 ft width, south → north
- **Z axis:** vertical upward

Bounds:
```
0 ≤ X ≤ 48 ft
0 ≤ Y ≤ 26 ft
0 ≤ Z ≤ final roof height
```

Concept height:
- eave Z ≈ 12 ft
- ridge Z ≈ 17 ft

## 3. Plan zoning

### X direction
| X range | Length | Use |
|---|---:|---|
| 0–4 ft | 4 ft | west cross/service zone |
| 4–44 ft | 40 ft | 10-stall active run |
| 44–48 ft | 4 ft | east cross/service zone |

### Y direction
| Y range | Width | Use |
|---|---:|---|
| 0–3 ft | 3.0 ft | south dirty/service/scraper strip |
| 3–8.5 ft | 5.5 ft | south cow platform |
| 8.5–10 ft | 1.5 ft | south manger |
| 10–16 ft | 6.0 ft | central feed alley |
| 16–17.5 ft | 1.5 ft | north manger |
| 17.5–23 ft | 5.5 ft | north cow platform |
| 23–26 ft | 3.0 ft | north dirty/service/scraper strip |

## 4. Stall grid

Each row contains 10 planning stalls.

Active stall X range = 4–44 ft = 40 ft.

```
stall width along X = 40 / 10 = 4 ft
```

South-row stall N:
```
X_start = 4 + (N-1) × 4
X_end   = X_start + 4
Y = 3 to 8.5 ft
```

North-row stall N:
```
X_start = 4 + (N-1) × 4
X_end   = X_start + 4
Y = 17.5 to 23 ft
```

These are concept stall modules and must be reviewed against final cow size and husbandry system.

## 5. Area accounting

### Full shed
```
26 × 48 = 1,248 ft²
```

### Dirty/service strips
```
2 × 3 × 48 = 288 ft²
```

### Cow platforms
```
2 × 5.5 × 40 = 440 ft²
```

### Mangers
```
2 × 1.5 × 40 = 120 ft²
```

### Central feed alley
```
6 × 48 = 288 ft²
```

Subtotal:
```
288 + 440 + 120 + 288 = 1,136 ft²
```

Remaining end-cross area within the stall/manger bands:
```
1,248 - 1,136 = 112 ft²
```

Total checks:
```
1,136 + 112 = 1,248 ft²
```

## 6. Concept floor levels

Use project datum:
```
shed finished floor level = Z 0.00
```

Suggested conceptual falls, subject to civil/livestock review:
- cow platform cross-fall toward dirty lane: about 1–1.5%
- dirty-lane longitudinal fall toward downstream collection: about 0.5–1.0%
- feed alley kept as dry and level as practical while still allowing washdown

Example only:
```
1.5% across 5.5 ft
fall = 5.5 × 0.015 = 0.0825 ft ≈ 0.99 in
```

Example longitudinal 1%:
```
48 × 0.01 = 0.48 ft = 5.76 in
```

The final slope must be reconciled with scraper manufacturer limits and site levels.

## 7. Roof geometry

Using concept eave/ridge heights:
- eave Z ≈ 12 ft at Y = 0 and Y = 26
- ridge Z ≈ 17 ft at Y = 13

Roof plane south:
connect line from (any X, Y=0, Z=12) to ridge (any X, Y=13, Z=17)

Roof plane north:
connect ridge to (any X, Y=26, Z=12)

Concept roof angle ≈ 21.04°.

## 8. Openings

Opening positions are **not FIXED** until the global site coordinate drawing is completed.

Required opening functions:
- feed/service access aligned with central feed alley
- animal access aligned with cow-yard route
- staff egress at both ends or equivalent safe escape
- equipment-removal path for scraper components
- roof access point for solar maintenance positioned outside animal traffic

## 9. Blueprint line classes for CAD/AI diagrams

Use:
- heavy line: external structural footprint
- medium line: stall rails/mangers
- dashed line: overhead utilities
- orange/brown line: manure flow
- cyan line: water
- dark blue line: electricity/data
- blue line: clean milk route outside shed
- green line: roof solar/electrical route
- **no green gas line through the shed**

## 10. Cross-section labels

Every cross-section should identify:
- 3 ft dirty strip
- 5.5 ft cow platform
- 1.5 ft manger
- 6 ft feed alley
- symmetric opposite row
- eave height
- ridge height
- roof slope
- ridge ventilation
- gutter
- fan mounting zone
- water-header height
- electrical tray height

## 11. Neighbor context for section images

Until the full global-coordinate file is approved, show adjacency qualitatively:
- cow yard on one side of shed
- milk/office toward clean/front side
- waste receiving downstream of manure path
- feed storage close to feed alley
- service lane outside animal interior

Do not infer new exact global coordinates from illustration alone.
