# MASTER IMAGE GUIDE — Prompts, Cameras and Rendering Workflow

## 1. Generation workflow
### Step A — choose a view ID
Use `VIEW-MATRIX.md`.

### Step B — load geometry
Read:
- `IMAGE.md`
- `MASTER-COORDINATES.md`
- `MASTER-SITE-PLAN.md`

### Step C — load visible sections
For every physical section visible, read its:
- `IMAGE.md`
- `BLUEPRINT.md`
- `ARCHITECTURE.md`

### Step D — select visual mode
- photoreal.
- orthographic.
- engineering overlay.
- cutaway.
- infographic.

### Step E — run image QA
Use root `IMAGE.md` checklist.

## 2. Conceptual master cameras
These are visualization cameras, not survey coordinates.

### TOP
Camera:
```
(32.5, 47.5, 150)
```
Target:
```
(32.5, 47.5, 0)
```

True orthographic / near-zero perspective.

### SOUTH / FRONT
Camera:
```
(32.5, -70, 35)
```
Target:
```
(32.5, 38, 8)
```

### NORTH / REAR
Camera:
```
(32.5, 160, 35)
```
Target:
```
(32.5, 60, 8)
```

### EAST / SERVICE LANE
Camera:
```
(120, 47.5, 32)
```
Target:
```
(43, 47.5, 8)
```

### WEST / LIVESTOCK
Camera:
```
(-60, 47.5, 32)
```
Target:
```
(25, 47.5, 8)
```

### SW AERIAL
```
camera (-45,-45,70)
target (32.5,47.5,8)
```

### SE AERIAL
```
camera (110,-45,70)
target (32.5,47.5,8)
```

### NW AERIAL
```
camera (-45,140,70)
target (32.5,47.5,8)
```

### NE AERIAL
```
camera (110,140,70)
target (32.5,47.5,8)
```

## 3. Master photoreal prompt recipe
Use:

```text
Create a realistic integrated 20-cow dairy + biogas + fertilizer + solar farm on an exact 65 ft ×95 ft rectangular plot.

Use PLANT-V1.0 DCF-1 coordinates exactly.

The east side is a continuous 14-ft-wide service lane from front to rear.

Show only physical Sections 01–15.

Front: office/vet/biosecurity, water utility, feed store and feed-unloading canopy.
Middle-west: 26×48 ft cow shed with controlled clean path to lane-facing milk room.
Behind cow shed: waste receiving/mixing then biogas digester.
Rear: cow yard, raw-gas holder, gas treatment, generator/electrical and fertilizer-processing building.
Place exactly 24 ×625 W solar modules on the cow-shed gable roof, 12 per roof plane.

Architecture is practical modern agro-industrial Bangladesh: galvanized steel, RCC process bases, durable metal roofs, clean functional circulation, monsoon-ready drainage, realistic tropical environment.

Preserve all open hygiene, service and maintenance buffers.
Do not move or resize any section.
Do not create buildings for Sections 16–23.
```

Then append the selected camera/view instruction.

## 4. Exact orthographic plan prompt
```text
Create a true orthographic top-down master site plan of PLANT-V1.0.

Plot = 65×95 ft.
South/front at bottom, north/rear at top.
West at left, east at right.
East service lane = X51–65 for full Y0–95.

Use every rectangle exactly from MASTER-COORDINATES.md.
Label physical Sections 01–15.
Show Section 15 only as rooftop solar on Section 01.
Show functional buffers B01–B06.
No perspective distortion.
No decorative relocation.
No extra buildings.

Include dimensions and section numbers.
Mark "DCF-1 DESIGN COORDINATES — SURVEYED Z PENDING."
```

## 5. Engineering flow overlay prompt
```text
Use the exact DCF-1 site geometry.

Overlay:
blue milk flow 01→03→14,
amber feed flow 14→06→05→01,
brown manure flow 01→07→08,
dark-green raw-gas flow 08→09→10,
light-green treated-gas flow 10→11,
yellow digestate flow 08→12,
cyan clean-water network from 13,
dark-blue electrical flow from 15 to main MDB and from 11 to Essential Load Board.

Keep clean and dirty drainage separate.
Do not change architecture.
```

## 6. Image dimensions
Recommended:
- master aerial: 16:9.
- top plan: 4:5 or square depending label density.
- service-lane panorama: 16:9.
- process overlay: 16:9.
- vertical dashboard/infographic: 4:5.

## 7. Section close-up rule
If the request zooms into one section:
- master files control placement/context.
- local section files control the actual close-up geometry.

Example:
for a Section 12 close-up, use Section 12 IMAGE.md as the primary visual-detail source after confirming its global location from the master.
