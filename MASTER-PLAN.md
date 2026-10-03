# MASTER PLAN — PLANT-V1.0

## 1. Purpose
This file is the single master entry point for the complete compact integrated dairy, manure, biogas, fertilizer, electrical, solar and farm-management project.

It consolidates Sections 01–23 without replacing their detailed engineering.

## 2. Project identity
- **Plant version:** PLANT-V1.0.
- **Coordinate freeze:** DCF-1.
- **Plot:** 65 ft × 95 ft = 6,175 ft² ≈ 573.68 m².
- **Herd:** 20 adult cows.
- **Physical plant sections:** 01–15.
- **Lifecycle/control sections:** 16–23.
- **Construction status:** not started.
- **IFC status:** pending survey, safety, vendor and authority hold-point closure.

## 3. Core business and engineering outputs
### Dairy
- Planning milk production: ~140 L/day.
- Two milking periods/day.
- Milk chilled rapidly toward ~4°C.
- Clean pickup through Section 14.

### Feed
- Planning concentrate: ~60 kg/day.
- Dry roughage: ~80 kg/day.
- Fresh forage: ~300 kg/day as-fed.
- Truck → Section 06 canopy → Section 05 store → Section 01 cows.

### Manure
- Fresh dung: ~300 kg/day.
- Collection basis: ~270 kg/day.
- Dilution water: ~270 L/day.
- Slurry: ~0.54 m³/day.

### Digester / gas
- Digester working volume: ~20 m³.
- HRT: ~37 days planning.
- Biogas: ~8.10–9.18 m³/day.
- Gas chain: 08 → 09 → 10 → 11.

### Electrical
- Biogas generator: 5 kW rated, ~4 kW normal planning operation.
- Gross biogas electricity: ~14.5–16.5 kWh/day.
- Solar: 15.0 kWp; ~58.35 kWh/day planning.
- Combined gross renewable generation: ~72.9–74.8 kWh/day planning.

### Fertilizer
- Base finished solid product: ~38.7 kg/day.
- Base annual planning: ~14.1 t/year.
- Liquid digestate: ~0.456 m³/day base case.

### Water
- Normal demand: ~3.30 m³/day.
- Design +15%: ~3.79 m³/day.
- Hot-weather design: ~4.25 m³/day.
- Storage: 8 m³ ground + 2 m³ overhead = 10 m³.

## 4. Whole-site functional order
Front / public / logistics:
- Section 04 Office + vet + biosecurity.
- Section 13 Water utility.
- Section 05 Feed store.
- Section 06 Feed unloading canopy.

Dairy core:
- Section 01 Cow shed.
- Section 03 Milk room + chiller.
- controlled clean cow-to-milk transfer zone.

Dirty/process chain:
- Section 07 Waste receiving + mixing.
- Section 08 Biogas digester.

Rear energy/process:
- Section 09 Gas storage.
- Section 10 Gas treatment.
- Section 11 Generator + electrical.
- Section 12 Fertilizer processing.

Site logistics:
- Section 14 east-side truck/service lane.

Roof energy:
- Section 15 solar on Section 01 roof only.

## 5. Global DCF-1 rule
Global origin:
- southwest/front property corner = (0,0).
- X west→east.
- Y front→rear.

East service lane:
- X=51–65 ft.
- Y=0–95 ft.

Use [MASTER-COORDINATES.md](MASTER-COORDINATES.md) for all exact rectangles.

## 6. Clean/dirty/process separation
### Clean
04 / 05 / 06 / 03 / 13 plus controlled milk path.

### Livestock
01 / 02.

### Dirty biological
07 / 08 / wet part of 12.

### Gas / energy
09 / 10 / 11 gas train.

### Traffic
14.

Rules:
- milk does not cross manure/digestate.
- potable water has backflow protection.
- dirty liquid does not enter clean stormwater.
- raw gas never bypasses Section 10.
- solar does not energize the isolated generator bus in baseline topology.

## 7. Master process flows
Milk:
01 → 03 → 14 → milk buyer.

Feed:
14 → 06 → 05 → 01.

Manure:
01 → 07 → 08.

Gas:
08 → 09 → 10 → 11.

Digestate:
08 → 12 → solid/liquid products.

Water:
13 → 01 / 03 / 04 / 07 / 12 and other approved users.

Electricity:
15 → main MDB/grid.
11 → ATS → Essential Load Board.

## 8. Financial control
Current gross control budget for Sections 01–19:
```
Tk26,972,958
≈Tk269.73 lakh
```

Illustrative full-new funding with:
- 20 cows at Tk250k each.
- 3 months base working capital.

```
≈Tk33,361,083
≈Tk333.61 lakh
```

Current illustrative base business case is negative; see Section 23 and [MASTER-BUSINESS.md](MASTER-BUSINESS.md).

## 9. Construction control
Indicative planning duration:
- ~40 weeks after applicable IFC/NTP.
- critical path runs through digester → biological startup → gas → generator → integrated trial.

Use [CONSTRUCTION.md](CONSTRUCTION.md).

## 10. Operations
Core planning team:
- farm/operations manager ×1.
- livestock/milking operators ×2.
- utility/process technician ×1.
- feed/cleaning/logistics ×1.
- specialists/vet on-call.

Use [OPERATIONS-MAINTENANCE.md](OPERATIONS-MAINTENANCE.md).

## 11. Master image rule
Before any whole-farm image:
1. Read root [IMAGE.md](IMAGE.md).
2. Read [MASTER-COORDINATES.md](MASTER-COORDINATES.md).
3. Read [VIEW-MATRIX.md](VIEW-MATRIX.md).
4. Identify every visible physical section.
5. Read each visible section's `IMAGE.md`, `BLUEPRINT.md` and `ARCHITECTURE.md`.
6. Render only Sections 01–15 as physical plant.
7. Render Sections 16–23 only as overlays/infographics/data if requested.

## 12. Master approval status
Planning/design coordination:
- highly developed.

Not yet final construction IFC because outstanding items include:
- surveyed RL/topography.
- flood/groundwater.
- outfall/inverts.
- fire/emergency approval.
- hazardous-area classification.
- utility service confirmation.
- vendor shop drawings.
- structural signoffs.
- FID/commercial approval.

## 13. Source-of-truth hierarchy
Whole plant:
- root master files.

Local geometry/equipment:
- section-specific files.

External final authority:
- licensed engineer/architect/veterinarian/fire/electrical specialists.
- approved vendor documentation.
- current Bangladesh authorities/regulations.
