# Cow Shed — Architecture Report

## 1. Design intent

The cow shed is the central production space of the plant. It must simultaneously support animal comfort, feeding, drinking, milking access, automated manure removal, tropical ventilation, rooftop solar and short human travel paths.

The design deliberately avoids placing gas-processing equipment, fertilizer handling or truck traffic inside the animal zone.

## 2. Governing baseline

| Item | Value | Tag |
|---|---:|---|
| Footprint | 26 × 48 ft | FIXED |
| Floor area | 1,248 ft² / 115.94 m² | CALCULATED |
| Adult cow capacity | 20 | FIXED |
| Row arrangement | 2 rows × 10 | ASSUMPTION |
| Eave height | ~12 ft | ASSUMPTION |
| Ridge height | ~17 ft | ASSUMPTION |
| Roof form | Symmetrical gable | ASSUMPTION |
| Roof-mounted solar | 15 kWp project target | FIXED at project level; module layout VENDOR |

All ASSUMPTION values require architect/structural/livestock review before construction.

## 3. Architectural geometry

### 3.1 Floor
```
A = L × W
A = 48 ft × 26 ft
A = 1,248 ft²
```

Metric:
```
1,248 × 0.09290304 = 115.943 m²
```

### 3.2 Roof pitch concept
With a 12 ft eave and 17 ft ridge:

```
rise = 17 - 12 = 5 ft
half span = 26 / 2 = 13 ft
pitch = 5 / 13 = 0.3846 = 38.46%
roof angle = arctan(5/13) ≈ 21.04°
```

Approximate sloped roof area without overhang:
```
roof area ≈ floor plan area / cos(21.04°)
≈ 1,248 / cos(21.04°)
≈ 1,337 ft²
```

For early material allowance, adding 10% for overhang/waste:
```
1,337 × 1.10 ≈ 1,471 ft²
```

This is a **planning quantity**, not a roofing purchase order.

### 3.3 Approximate internal air volume
Rectangular volume to eave:
```
1,248 × 12 = 14,976 ft³
```

Gable prism:
```
triangle area = 0.5 × 26 × 5 = 65 ft²
gable volume = 65 × 48 = 3,120 ft³
```

Total:
```
18,096 ft³ ≈ 512.4 m³
```

The high roof volume supports heat dilution and natural ventilation.

## 4. Spatial architecture

The width is divided into seven functional bands:

| Band | Width | Function |
|---|---:|---|
| South dirty/service strip | 3.0 ft | scraper/manure/service |
| South cow platform | 5.5 ft | cow standing/resting |
| South manger | 1.5 ft | feed edge |
| Central feed alley | 6.0 ft | feed movement and worker route |
| North manger | 1.5 ft | feed edge |
| North cow platform | 5.5 ft | cow standing/resting |
| North dirty/service strip | 3.0 ft | scraper/manure/service |

Total:
```
3 + 5.5 + 1.5 + 6 + 1.5 + 5.5 + 3 = 26 ft
```

The length is organized as 4 ft end zone + 40 ft stall run + 4 ft end zone.

## 5. Roof and tropical-climate strategy

### 5.1 Roof
Recommended concept:
- lightweight corrosion-protected steel structure
- insulated or heat-reflective metal roofing
- continuous ridge ventilation or ventilated ridge cap
- generous side openings
- rain-protected eaves
- guttering independent of manure drainage
- structural provision for rooftop solar

### 5.2 Side wall concept
Instead of fully enclosed masonry walls:
- durable low splash/kick wall near floor
- open upper wall zone
- mesh, rails or adjustable rain curtain as required
- large cross-ventilation path from one long side to the other

### 5.3 Ventilation
The shed should favor natural cross-flow and stack effect first, with circulation fans added where measured heat/humidity requires them.

Fan quantity and airflow must be selected from actual fan curves and final ventilation design; the architecture only reserves mounting positions and power routes.

## 6. Elevation concept

### Long elevations
- mostly open
- repetitive structural bays
- roof eaves around 12 ft conceptually
- gutters along both long edges
- fan/curtain mounting line below eaves
- no gas storage, gas treatment or generator exhaust on the cow-shed wall

### Gable elevations
- central feed/service access
- open gable ventilation where rain protection allows
- solar cabling leaves roof through a controlled electrical route, not through wet manure lanes

## 7. Material concept

| Element | Planning material concept |
|---|---|
| Primary frame | Hot-dip galvanized or protected structural steel |
| Purlins | Galvanized cold-formed steel |
| Roof | Color-coated metal sheet / insulated panel depending heat budget |
| Floor | Reinforced concrete with textured non-slip finish |
| Manger | Smooth dense concrete or durable prefabricated system |
| Stall rails | Galvanized steel |
| Splash zones | Washable concrete/masonry finish |
| Fasteners | Corrosion-resistant |
| Gutters | Corrosion-resistant metal/PVC sized by rainfall study |
| Electrical enclosures | Dust/moisture-resistant agricultural/industrial grade |

## 8. Hygiene architecture

The architecture separates:
- **clean center:** feed alley and feed delivery
- **animal platform:** cow rows
- **dirty outside lanes:** manure/scraper zones

Milk is not stored here. Feed is not stored on the floor inside the dirty zone. Manure exits one direction toward the waste system.

## 9. Structural concept

The preferred structure is a regular steel bay system because it:
- keeps internal columns away from cow rows and scraper routes
- provides a clear feed alley
- supports a lightweight roof
- allows solar load to be considered from the start
- is easy to ventilate

Final member sizes, column bases, wind loads, cyclone loads, seismic design, foundation sizes and solar dead/live loads are **STRUCTURAL ENGINEER** items.

## 10. Architectural interfaces with adjacent sections

When shown in a wider plant image:
- cow yard should remain directly accessible from the shed
- milk-room path should be short and clean
- feed-store route should connect to the central feed alley
- waste-receiving route should be downstream of manure lanes
- service-lane vehicles should not enter the cow interior

## 11. Performance targets

The detailed design should verify:
- no standing water on animal floor
- direct rain is controlled at open sides
- airflow reaches both cow rows
- roof heat is controlled
- manure moves without crossing feed
- staff can inspect every cow
- scraper equipment is removable/serviceable
- solar system can be serviced without damaging roof or blocking ventilation

## 12. Professional verification

Before construction, a Bangladesh-qualified architect/engineer and livestock professional should verify:
- local building/setback rules
- structure and foundations
- roof wind loading
- animal-space requirements
- drainage slopes
- electrical protection
- solar mounting
- manure-equipment loads
- fire/emergency access
