# Cow Shed — AI Image Generation Guide

## 1. Purpose

This file lets an AI generate the cow shed from almost any camera position without redesigning it.

The image model must reproduce the approved architecture, not invent a new shed.

---

## 2. Fixed visual identity

### Geometry
- rectangular 48 ft long × 26 ft wide shed
- symmetrical gable roof
- concept eave about 12 ft
- concept ridge about 17 ft
- two cow rows, 10 positions each
- 6 ft central feed alley
- mangers both sides of feed alley
- outer manure/service lanes
- open-sided tropical architecture

### Materials
- galvanized/protected steel frame
- light-colored metal roof
- reinforced textured concrete floor
- galvanized stall rails
- concrete/feed-safe mangers
- industrial water troughs
- exposed but organized overhead water/electrical services

### Equipment visible
- 20 cow positions
- scraper lanes
- fans
- LED fixtures
- water troughs
- roof gutters
- optional sensors/CCTV
- rooftop solar array when roof is visible

### Equipment not allowed inside
- biogas digester
- gas holder
- gas treatment vessels
- generator
- fertilizer machine
- large feed storage stacks

---

## 3. Local 3D coordinate system

Use the blueprint coordinate frame:
- X = 0–48 ft, west to east
- Y = 0–26 ft, south to north
- Z = height
- origin = southwest floor corner

Target center:
```
(24, 13, 5)
```

Concept roof:
- eaves Z ≈ 12 ft
- ridge Z ≈ 17 ft

---

## 4. Camera presets

The coordinates below are conceptual camera positions in feet relative to the local section.

### Top orthographic
```
camera = (24, 13, 70)
target = (24, 13, 0)
projection = orthographic
```

### South elevation
```
camera = (24, -45, 8)
target = (24, 13, 7)
```

### North elevation
```
camera = (24, 71, 8)
target = (24, 13, 7)
```

### West elevation
```
camera = (-45, 13, 8)
target = (24, 13, 7)
```

### East elevation
```
camera = (93, 13, 8)
target = (24, 13, 7)
```

### Southwest aerial
```
camera = (-25, -25, 32)
target = (24, 13, 5)
```

### Southeast aerial
```
camera = (73, -25, 32)
target = (24, 13, 5)
```

### Northwest aerial
```
camera = (-25, 51, 32)
target = (24, 13, 5)
```

### Northeast aerial
```
camera = (73, 51, 32)
target = (24, 13, 5)
```

---

## 5. Interior camera presets

### Feed alley west → east
```
camera = (5, 13, 5.5)
target = (43, 13, 4)
lens = ~24–28 mm equivalent
```

Image must show:
- central alley
- both mangers
- both cow rows
- roof frame
- fans
- lights

### Feed alley east → west
```
camera = (43, 13, 5.5)
target = (5, 13, 4)
```

### South cow row
```
camera = (24, 9.5, 5.5)
target = (24, 5.5, 3.5)
```

### North cow row
```
camera = (24, 16.5, 5.5)
target = (24, 20.5, 3.5)
```

### South scraper lane
```
camera = (5, 1.5, 3)
target = (43, 1.5, 1.5)
```

Show:
- dirty lane
- scraper mechanism
- cow platform edge
- downstream direction arrow if infographic

### Roof/solar
```
camera = (24, 13, 35)
target = (24, 13, 14)
```

Show:
- roof ridge
- gutters
- solar array
- roof access/maintenance logic
- no impossible panels beyond roof edge

---

## 6. Cross-section image

Use an orthographic cut approximately through X = 24 ft.

Required sequence south → north:
```
3 ft dirty
5.5 ft cow
1.5 ft manger
6 ft feed alley
1.5 ft manger
5.5 ft cow
3 ft dirty
```

Show:
- floor slopes conceptually
- trough/rail
- roof eave/ridge
- ridge ventilation
- fan mounting zone
- water header
- electrical tray
- solar above roof

---

## 7. Blueprint image style

For technical top views:
- white or pale background
- black structural lines
- dimension strings
- grid/coordinates
- no perspective distortion
- cows as simplified plan symbols
- utility overlays color-coded

Utility colors:
- manure = orange/brown
- water = cyan
- electrical/data = dark blue
- solar electrical = green
- milk route = blue
- **gas = absent**

---

## 8. Photorealistic style

Use:
- tropical Bangladesh daylight
- humid climate
- practical agricultural materials
- clean but actively used farm
- realistic concrete texture
- galvanized steel
- realistic Holstein/crossbred dairy cows if breed is not otherwise specified
- visible fans, troughs, gutters and scraper lanes

Avoid:
- luxury architecture
- decorative landscaping inside working shed
- impossible glass walls
- indoor residential finishes
- random extra machinery

---

## 9. Adjacent-space context

For a section-only image, fill frame primarily with the cow shed.

For a wider context image, nearby spaces may be partially visible:
- cow yard
- milk/office clean side
- feed/service side
- waste receiving downstream

Do not move adjacent sections merely to improve composition.

Exact global positions should come from the future site coordinate master.

---

## 10. Time-of-day variants

### Day
Primary engineering view.

### Early morning
Milking preparation; cool natural light.

### Midday
Show shade and ventilation.

### Evening
Lights on, cows settled.

### Night
Use only for operations/safety visualization. Keep industrial lighting realistic.

---

## 11. Weather variants

Allowed when requested:
- dry sunny
- cloudy
- monsoon rain exterior
- hot summer
- night

In rain images:
- roof runoff must go to gutters
- no rainwater should visually pour into manure sump
- interior should remain reasonably protected

---

## 12. Image prompt construction template

```text
Create a [view type] of Section 01 cow shed for PLANT-V1.0.
Exact shed footprint: 48 ft long × 26 ft wide.
Use local XYZ coordinate system from BLUEPRINT.md.
Camera: [preset].
Architecture: open-sided tropical steel dairy shed, gable roof, eave about 12 ft, ridge about 17 ft.
Interior: two rows of 10 cow positions, central 6 ft feed alley, 1.5 ft mangers, 5.5 ft cow platforms, 3 ft outer manure/scraper lanes.
Materials: galvanized steel, textured concrete, light metal roof.
Show [utilities/equipment].
Do not show gas equipment inside.
Do not change dimensions or add buildings.
If context is visible, preserve plant adjacency.
[photorealistic / blueprint / technical infographic] style.
```

---

## 13. Negative constraints

Never generate:
- one-row shed
- 30+ cows
- enclosed air-conditioned barn
- generator beside cow stalls
- biogas tank inside shed
- manure channel through feed alley
- milk storage in manure lane
- solar panels floating beyond roof
- multiple floors
- random room partitions
- residential furniture

---

## 14. Image QA checklist

Before accepting:
- [ ] 48 × 26 proportion looks correct
- [ ] 20 cow positions maximum
- [ ] two rows
- [ ] central feed alley
- [ ] two outside manure lanes
- [ ] gable roof
- [ ] ventilation visible
- [ ] no gas equipment
- [ ] water/electrical routes plausible
- [ ] solar only on roof when shown
- [ ] adjacent spaces do not contradict master plan
