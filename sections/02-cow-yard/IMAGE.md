# Cow Yard — Canonical IMAGE.md

## Purpose
This is the single image source of truth for Section 02.

## Fixed geometry
- 18 × 28 ft = 504 ft²
- active zone = 18 × 24 ft
- service/drain strip = 18 × 4 ft
- shade canopy = 12 × 18 ft
- 10 cows maximum shown in normal operating images
- two-batch rotational concept for the 20-cow herd

## Image math
```
18 × 28 = 504 ft²
18 × 24 = 432 ft² active
12 × 18 = 216 ft² shade
216 / 432 = 50% active-zone shade
40.13 m² / 10 = 4.01 m²/cow
```

## Coordinate system
- origin southwest
- X 0–28 ft west→east
- Y 0–18 ft south→north
- Z vertical

## Required visual zones
- X 0–12 shaded active
- X 12–24 open active
- X 24–28 service/drain
- cattle gate toward shed side
- trough in service strip
- dirty drain along east edge

## Visual identity
- compact paved cattle yard
- galvanized/painted fence
- practical steel shade canopy
- non-slip concrete
- one livestock trough
- tropical Bangladesh farm context
- no decorative garden treatment

## Prompt requirements
Every prompt must state:
- PLANT-V1.0
- Section 02
- 18 × 28 ft exact footprint
- 10 cows maximum in yard
- 12 × 18 ft shade canopy
- paved slope to dirty drain
- connection to cow shed
- no biogas/generator equipment

## Utility overlay colors
- water cyan
- dirty runoff brown/orange
- clean canopy rain light blue
- electrical/data dark blue
- gas absent

## Negative constraints
No 20-cow crowding image, no pasture, no mud yard, no generator, no gas holder, no feed warehouse, no indoor barn, no random extra structures.

## QA
Reject if:
- more than 10 cows shown for normal operation
- shade/open/service zones drift
- yard is not 18:28 proportion
- drain is omitted in technical views
- clean and dirty water are merged
- image invents extra buildings
