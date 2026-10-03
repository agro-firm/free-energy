---
name: site-coordinate-freeze
description: Maintain the DCF-1 global X/Y coordinate register, setting-out controls, clash checks and survey-to-IFC transition.
---

# Site Coordinate Freeze Skill

## Version
DCF-1 / PLANT-V1.0.

## Boundary
P0 SW/front = (0,0)
P1 SE/front = (65,0)
P2 NE/rear = (65,95)
P3 NW/rear = (0,95)

## Rules
1. Section rectangles may rotate globally but local section geometry/capacity does not change.
2. X/Y changes require clash + area + interface review.
3. Z coordinates are not frozen until topographic survey.
4. Any vendor package exceeding its rectangle triggers change control.
5. Full-site images must use this register.
6. High safety/clash holds override coordinate convenience.

## Coordinate source
See sections/17-master-site-coordinate-freeze/COORDINATE-REGISTER.md.
