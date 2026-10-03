# MASTER IMAGE — Canonical Whole-Plant Image Authority

## 1. Purpose
This file controls every whole-farm image, render, diagram, aerial, blueprint, cutaway, process overlay and master visualization for PLANT-V1.0.

A master image is not allowed to redesign the plant.

## 2. Mandatory source order before generating any image
Read in this exact order:

1. `MASTER-PLAN.md`
2. `MASTER-COORDINATES.md`
3. `MASTER-SITE-PLAN.md`
4. `VIEW-MATRIX.md`
5. `MASTER-SECTION-REFERENCES.md`
6. For every visible Section 01–15:
   - local `IMAGE.md`
   - local `BLUEPRINT.md`
   - local `ARCHITECTURE.md`
   - any special layout file listed in `MASTER-SECTION-REFERENCES.md`

If one image shows Sections 01, 03, 07 and 14, read all four local image/blueprint/architecture packages before rendering.

## 3. Physical vs nonphysical rule
Physical site sections:
```
01–15
```

Management/control sections:
```
16–23
```

Sections 16–23 are NEVER additional buildings.

They may appear only as:
- labels.
- overlays.
- flow arrows.
- safety zones.
- schedules.
- construction phases.
- KPI dashboards.
- financial graphics.

## 4. Global fixed geometry
Plot:
```
65 ft ×95 ft
```

Origin:
```
southwest/front = (0,0)
```

East service lane:
```
X51–65
Y0–95
```

Physical rectangles:
- 04: X0–12 Y0–15.
- 13: X12–20 Y0–12.
- 05: X21–41 Y0–18.
- 06: X41–51 Y0–18.
- 01: X0–26 Y18–66.
- 03: X37–51 Y18–36.
- 07: X26–40 Y37–47.
- 08: X26–46 Y47–63.
- 11: X39–51 Y65–79.
- 02: X0–18 Y66–94.
- 09: X18–28 Y66–78.
- 10: X28–38 Y66–74.
- 12: X29–51 Y79–95.
- 14: X51–65 Y0–95.
- 15: roof of 01 only.

## 5. Solar lock
Section 15:
- exactly 24 modules.
- 625 W each.
- 12 modules each roof plane.
- 15.0 kWp.
- no ground-mount array.
- no panel beyond roof edge.
- keep ridge/eave/service clearance.

## 6. Cow-shed lock
Section 01:
- 26×48 ft.
- gable roof.
- two 10-cow rows.
- central feed alley.
- manure/service lanes.
- rooftop solar.

Do not turn it into a free-stall barn of another geometry.

## 7. Service-lane lock
Section 14:
- full 14 ft physical width.
- one truck at a time.
- east boundary.
- no internal U-turn.
- no permanent parking/storage.

A master truck image uses a Tata LPT-709-class rigid truck planning envelope unless a later approved vehicle replaces it.

## 8. Clean/dirty rendering logic
Clean/public:
- 03,04,05,06,13.

Livestock:
- 01,02.

Dirty/process:
- 07,08,12 wet process.

Gas/energy:
- 09,10,11.

Traffic:
- 14.

Do not visually mix:
- milk hose with manure.
- feed unload with fertilizer spill.
- clean storm drain with digestate.
- raw gas with public/clean front zone.

## 9. Master visual language
### Photoreal images
Style:
- modern practical Bangladesh dairy/agro-industrial farm.
- clean but operational.
- galvanized/painted steel.
- RCC process bases.
- durable metal roofs.
- tropical daylight.
- realistic service access.
- no luxury/resort treatment.

### Engineering images
Color code:
- milk = blue.
- feed = amber/orange.
- manure = brown.
- raw biogas = dark green.
- treated gas = light green.
- digestate/fertilizer = yellow/gold.
- clean water = cyan.
- electrical = dark blue.
- traffic = grey.
- safety/emergency = red.
- solar = gold.

## 10. Z/elevation rule
DCF-1 fixes X/Y.

Surveyed Z is still controlled by Section 18.

Photoreal/master 3D images may use conceptual section heights from local architecture files, but must not label invented RL/elevation values as surveyed/IFC.

Engineering level drawings must say:
```
DESIGN COORDINATION — SURVEYED Z/IFC LEVELS PENDING
```
unless real survey data has been inserted.

## 11. Camera coordinate convention
Conceptual camera coordinates use:
- X/Y in site feet.
- Z only for visualization.
- target near site center (32.5,47.5).

These camera Z values are not survey elevations.

## 12. Required master image categories
- exact orthographic site plan.
- labeled section plan.
- four corner aerials.
- front/public view.
- east service-lane view.
- west livestock view.
- rear energy/fertilizer view.
- clean/dirty zoning.
- milk/feed/manure/gas/digestate flows.
- water network.
- power network.
- drainage network.
- safety/hazard overlay.
- construction phases.
- operations dashboard.
- business/financial infographic.

## 13. Negative prompts — mandatory
Never show:
- plot wider/longer than 65×95 ft.
- service lane on west side.
- extra permanent buildings.
- Sections 16–23 as physical buildings.
- changed section footprints.
- duplicate digester or generator.
- solar on ground.
- more/less than 24 solar modules in a master roof view.
- two trucks passing in lane.
- internal truck U-turn.
- milk and manure crossing.
- raw gas bypassing treatment.
- dirty liquid entering clean stormwater.
- generator and grid illegally backfeeding.
- fake surveyed RLs.
- fake FSCD approval.
- fake vendor-specific equipment not approved.

## 14. Image QA checklist
Before accepting a generated master image:

### Boundary
- [ ] 65×95 ft proportions correct.
- [ ] front/rear orientation correct.
- [ ] east lane continuous.

### Physical sections
- [ ] every visible footprint is at correct coordinate.
- [ ] no overlap.
- [ ] no missing required physical section.
- [ ] no extra section/building.

### Interfaces
- [ ] feed: 14→06→05.
- [ ] milk: 01→03→14.
- [ ] manure: 01→07→08.
- [ ] gas: 08→09→10→11.
- [ ] fertilizer: 08→12→14.
- [ ] solar only on 01.

### Details
- [ ] solar count/orientation correct.
- [ ] service lane width/traffic logic correct.
- [ ] section-specific equipment matches local files.
- [ ] utility colors correct in technical drawings.

### Status
- [ ] nonphysical Sections 16–23 shown only as overlays if requested.
- [ ] no invented IFC/survey approval.

If any item fails, regenerate rather than accepting the image as a design change.
