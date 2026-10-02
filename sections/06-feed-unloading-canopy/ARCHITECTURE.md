# Feed Unloading Canopy — Architecture Report

## 1. Design intent
This is a **side-unloading weather-protected transfer zone**. The farm vehicle stays in the service lane while workers move bags, pallets and fresh forage across a short covered apron into the feed store or same-day feed flow.

The canopy is intentionally only 10×18 ft because the 14-ft lane already provides truck space. Covering the whole truck would consume land without improving the main transfer path.

## 2. Geometry
```
10 × 18 = 180 ft²
180 × 0.09290304 = 16.7225 m²
```

## 3. Roof form
Single-slope lean-to:
- high edge at feed-store side: ~14 ft ASSUMPTION
- low edge at service-lane side: ~12 ft ASSUMPTION
- horizontal projection: 10 ft
- drop: 2 ft

Slope:
```
2 / 10 = 0.20 = 20%
```

Angle:
```
arctan(0.20) ≈ 11.31°
```

Sloped roof length:
```
sqrt(10² + 2²) = 10.198 ft
```

Roof area:
```
10.198 × 18 = 183.56 ft²
```

10% roofing/overhang allowance:
```
183.56 × 1.10 ≈ 201.92 ft²
```

## 4. Structural concept
Preferred:
- galvanized/protected steel frame
- front unloading face kept as open as possible
- rear columns/beam aligned to feed-store side
- front columns at ends where structurally feasible
- avoid a center front column that blocks bag/pallet movement

Actual spans, column sizes, foundations, wind loading and connection to Section 05 are STRUCTURAL ENGINEER items.

## 5. Truck relationship
The canopy does **not** function as a loading dock.

Local service-lane concept:
- service lane width = 14 ft
- concept farm-delivery truck envelope = 8 ft wide × 20 ft long × 10 ft high, ASSUMPTION
- truck remains parallel to the canopy
- target side clearance between truck and canopy edge = about 4 ft
- remaining outer-lane clearance = about 2 ft

Check:
```
4 ft unloading side + 8 ft truck + 2 ft outer clearance = 14 ft
```

Final swept-path and vehicle envelope must be checked using the actual supplier/delivery truck.

## 6. Vertical clearance
Low canopy edge:
```
12 ft concept
```

Concept truck height:
```
10 ft
```

Nominal vertical difference:
```
12 - 10 = 2 ft
```

The truck is not intended to drive under the canopy; this reserve keeps the edge clear of open doors/tarpaulins and improves rain protection.

## 7. Floor/apron
Recommended:
- reinforced concrete apron
- broom/non-slip finish
- concept 125 mm slab ASSUMPTION
- outward slope away from feed-store door
- no raised loading dock
- smooth threshold for platform trolley/pallet jack

## 8. Zone architecture
Along the 18-ft frontage:
- west 4 ft = fresh forage temporary stage
- center 10 ft = main bag/pallet transfer
- east 4 ft = inspection, hand trolley, chocks and safety equipment

All three zones extend the full 10-ft canopy depth.

## 9. Weather protection
Design for Bangladesh rain:
- roof overhang where feasible
- outer-edge gutter
- downpipe to clean stormwater
- floor slope outward
- trench/linear drain along lane edge
- feed-store door threshold protected from splash/runoff

## 10. Materials
| Element | Concept |
|---|---|
| Frame | galvanized/protected structural steel |
| Roof | color-coated metal sheet |
| Apron | reinforced concrete, non-slip |
| Drain grate | galvanized/ductile/engineered grate |
| Bollards/guards | painted/galvanized steel |
| Markings | high-visibility traffic paint |
| Gutter | corrosion-resistant metal/PVC |

## 11. Night use
Provide simple industrial LED/flood lighting with no glare toward driver or public road.

## 12. Safety
- truck brake set
- wheel chocks
- engine off during manual unloading unless vehicle equipment requires otherwise
- high-visibility worker PPE
- no worker between moving truck and fixed canopy
- no unstable stacked bags
- no pallet-jack use across excessive level changes

## 13. Important pallet-handling rule
A hand pallet truck moves pallets on **level floor**. It cannot safely bridge the height from a normal truck bed to ground by itself.

Palletized deliveries therefore require one of:
- truck tail lift
- forklift/stacker access
- approved lift/loading equipment
- unloading pallet at ground by supplier equipment

Do not improvise a steep ramp.
