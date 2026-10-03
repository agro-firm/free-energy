# Master Coordinates — DCF-1

## Global coordinate system
- Origin P0: southwest/front property corner = (0,0).
- X: west → east.
- Y: front → rear.
- Plot: X0–65 ft, Y0–95 ft.
- Service lane: X51–65 ft, Y0–95 ft.

## Exact physical-section rectangles
| Sec | Section | X | Y | Global size |
|---:|---|---|---|---|
| 04 | Office/vet/biosecurity | 0–12 | 0–15 | 12×15 ft |
| 13 | Water utility | 12–20 | 0–12 | 8×12 ft |
| 05 | Feed store | 21–41 | 0–18 | 20×18 ft rotated |
| 06 | Feed canopy | 41–51 | 0–18 | 10×18 ft |
| 01 | Cow shed | 0–26 | 18–66 | 26×48 ft |
| 03 | Milk room/chiller | 37–51 | 18–36 | 14×18 ft |
| 07 | Waste receiving/mixing | 26–40 | 37–47 | 14×10 ft rotated |
| 08 | Digester compound | 26–46 | 47–63 | 20×16 ft rotated |
| 11 | Generator/electrical | 39–51 | 65–79 | 12×14 ft |
| 02 | Cow yard | 0–18 | 66–94 | 18×28 ft |
| 09 | Gas storage | 18–28 | 66–78 | 10×12 ft |
| 10 | Gas treatment | 28–38 | 66–74 | 10×8 ft rotated |
| 12 | Fertilizer processing | 29–51 | 79–95 | 22×16 ft rotated |
| 14 | Service lane | 51–65 | 0–95 | 14×95 ft |
| 15 | Rooftop solar | Section 01 roof | Section 01 roof | 24×625 W modules |

## Section 15
Solar does not consume additional ground area.

Projection:
- X0–26.
- Y18–66.
- roof only.

## Functional open/buffer zones
### B01 — clean cow-to-milk transfer
- X26–37.
- Y18–36.
- 11×18 = 198 ft².

### B02 — milk/waste hygiene strip
- X26–51.
- Y36–37.
- 25 ft².

### B03 — waste-service strip
- X40–51.
- Y37–47.
- 110 ft².

### B04 — digester east service
- X46–51.
- Y47–63.
- 80 ft².

### B05 — digester/energy transition
- X26–39.
- Y63–66.
- 39 ft².

### B06 — treatment/generator service gap
- X38–39.
- Y66–74.
- 8 ft².

## Area check
Physical Sections 01–13:
```
4,000 ft²
```

Service lane:
```
1,330 ft²
```

Occupied:
```
5,330 ft²
```

Plot:
```
6,175 ft²
```

Functional residual:
```
845 ft²
=13.68%
```

## Z rule
Global X/Y is design-frozen.

Surveyed Z is not frozen.

Use Section 18 before any drawing claims real ground RL, drain invert, road level or flood elevation.

## Change rule
Any movement or resizing of a Section 01–15 global rectangle requires:
- Section 17 clash review.
- root master-file update.
- affected local section update.
- image-rule update.
