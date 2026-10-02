# Cow Shed — Canonical IMAGE.md

## Purpose
This is the single section-level source for image generation. It converts the engineering geometry into reproducible visual instructions without allowing images to redefine the design.

## Fixed geometry
- footprint: 48 ft × 26 ft
- 20 cow positions
- 2 rows × 10
- width sequence: 3 / 5.5 / 1.5 / 6 / 1.5 / 5.5 / 3 ft
- length: 4 ft end zone + 40 ft stall run + 4 ft end zone
- concept eave: ~12 ft ASSUMPTION
- concept ridge: ~17 ft ASSUMPTION
- gable roof
- rooftop solar belongs above the shed
- manure lanes outside cow rows
- no biogas equipment inside

## Geometry checks
```
48 × 26 = 1,248 ft²
3 + 5.5 + 1.5 + 6 + 1.5 + 5.5 + 3 = 26 ft
4 + 40 + 4 = 48 ft
40 / 10 = 4 ft planning stall module
```

## Image coordinate system
- origin = southwest floor corner
- X = 0–48 ft west→east
- Y = 0–26 ft south→north
- Z = vertical
- center = (24,13,0)

## Required view classes
Top orthographic, four elevations, four aerial corners, feed-alley views in both directions, each cow row, scraper lane, roof/solar, cross-section, utilities overlay, airflow, night operation and neighboring-section context.

## Prompt rules
Every prompt must explicitly state:
- PLANT-V1.0
- exact footprint
- exact two-row arrangement
- central feed alley
- outside manure lanes
- open-sided tropical steel shed
- galvanized rails / concrete floor / metal roof
- no generator, gas holder, digester or fertilizer machine inside

## Utility colors
- water = cyan
- manure = brown/orange
- stormwater = light blue
- electrical/data = dark blue
- solar electrical = green
- milk route = blue
- gas = absent inside Section 01

## Negative constraints
No extra floors, no luxury interior, no glass commercial barn, no single-row layout, no more than 20 cows, no manure through feed alley, no gas line through shed, no impossible roof solar.

## QA
Reject an image if dimensions, cow count, row count, feed alley, manure lanes, roof form or utility routing contradict the blueprint.

Detailed prompts and camera presets are in `images/IMAGE-GUIDE.md` and `images/VIEW-MATRIX.md`.
