# Feed Store — Architecture Report

## 1. Design intent
The feed store is a dry, pest-controlled, weather-tight warehouse for short-duration dairy feed inventory. It is deliberately compact and depends on frequent delivery instead of months of stock.

## 2. Geometry
```
18 × 20 = 360 ft²
360 × 0.09290304 = 33.4451 m²
```

At 12 ft clear height:
```
360 × 12 = 4,320 ft³
≈ 122.33 m³
```

## 3. Plan architecture
Local coordinate system:
- X = 0–20 ft west→east
- Y = 0–18 ft south→north

### Zone A — Receiving / quarantine
```
20 × 4 = 80 ft²
```
Functions:
- unload from Section 06
- check bag condition
- check supplier/batch/date
- weigh sample/delivery
- isolate wet/torn/mold-suspect feed before acceptance

### Zone B — Dry storage
```
20 × 10 = 200 ft²
```

Sub-zones:
- west dry roughage: 8 × 10 = 80 ft²
- center aisle: 4 × 10 = 40 ft²
- east concentrate/rack zone: 8 × 10 = 80 ft²

### Zone C — Preparation / dispatch
```
20 × 4 = 80 ft²
```

Sub-zones:
- weigh/mix: 8 × 4 = 32 ft²
- mineral/premix: 4 × 4 = 16 ft²
- cleaning/pest tools: 4 × 4 = 16 ft²
- dispatch staging: 4 × 4 = 16 ft²

Area check:
```
80 + 200 + 80 = 360 ft²
```

## 4. Building form
Recommended concept:
- enclosed rectangular feed warehouse
- raised dry slab/plinth
- gable metal roof
- eave ≈12 ft ASSUMPTION
- ridge ≈15 ft ASSUMPTION
- high-level louvered ventilation
- insect/rodent screens
- weather-sealed doors
- light-colored roof to reduce heat

## 5. Roof geometry
Half span:
```
18 / 2 = 9 ft
```

Rise:
```
15 - 12 = 3 ft
```

Pitch:
```
3 / 9 = 0.3333 = 33.33%
```

Angle:
```
arctan(3/9) ≈ 18.43°
```

Approximate sloped roof area without overhang:
```
360 / cos(18.43°) ≈ 379.5 ft²
```

With 10% planning allowance:
```
379.5 × 1.10 ≈ 417.5 ft²
```

## 6. Moisture-control architecture
The store should be physically dry before relying on equipment:
- raised finished floor above adjacent exterior level
- damp-proof membrane
- roof overhang
- sealed roof and wall joints
- high-level ventilation
- screened louvers
- no water pipes over feed stacks if avoidable
- pallets/racks keeping feed off floor
- wall clearance for inspection

Concept operational target:
- maintain a visibly dry store
- target RH around or below 65% where practical
- investigate prolonged RH above ~70%
These are operational ASSUMPTIONS, not regulatory limits.

## 7. Pest-control architecture
- sealed lower wall/floor junction
- rodent-resistant door threshold
- insect-screened vents
- no permanent open wall gaps
- perimeter inspection strip
- pallet/rack clearance for traps and cleaning
- no vegetation touching external wall

## 8. Fire architecture
Dry roughage is combustible.
Design principles:
- no smoking
- no hot work without permit/control
- keep electrical panel clear of hay/straw
- no fuel storage
- no gas equipment
- fire extinguisher and response system per professional fire-risk review
- keep exit/aisle unobstructed

## 9. Materials
| Element | Concept |
|---|---|
| Frame | galvanized/protected steel |
| Roof | color-coated metal sheet / insulated option |
| Wall | metal cladding or durable masonry/steel hybrid |
| Floor | reinforced dry concrete with DPM |
| Rack | powder-coated/galvanized steel |
| Pallets | food/feed-safe plastic or treated durable pallet |
| Doors | steel, weather/pest sealed |
| Louvers | screened galvanized/aluminum |

## 10. Structural note
Average stored-feed loads are modest, but rack/pallet point loads can be much higher. Structural floor design must use actual rack and pallet loads rather than average room loading.
