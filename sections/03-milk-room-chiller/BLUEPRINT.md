# Milk Room + Chiller — Blueprint and XYZ Specification

## Local coordinates
- origin: southwest floor corner
- X: west→east, 0–18 ft
- Y: south→north, 0–14 ft
- Z: vertical

## Zone schedule
| Zone | X | Y | Size | Area |
|---|---|---|---|---:|
| CIP/wash | 0–6 | 0–8 | 6×8 ft | 48 ft² |
| Receive/test | 0–6 | 8–14 | 6×6 ft | 36 ft² |
| Chiller/service | 6–13 | 0–14 | 7×14 ft | 98 ft² |
| Dispatch | 13–18 | 0–8 | 5×8 ft | 40 ft² |
| Clean ingress | 13–18 | 8–14 | 5×6 ft | 30 ft² |

## Equipment centers — planning only
- bulk milk chiller center: about (9.5, 7)
- wash sink/CIP station: about (2.5, 4)
- receiving/filter bench: about (2.5, 11)
- testing bench/handwash: about (1.5, 12.5)
- dispatch hose point: about (15.5, 3)
- clean milk ingress connection: about (15.5, 11)

## Doors
- dispatch door south wall: X ≈ 13.5–17.5, Y=0
- clean ingress north wall: X ≈ 14–17.5, Y=14

## Floor drains
Concept:
- FD-01 wash zone: around (3,3)
- FD-02 chiller/service zone: around (10,5)

Provide local floor falls to drains; avoid long cross-room flow.

## Floor slope
Planning 1.5% over a 7 ft local run:
```
7 × 0.015 = 0.105 ft
= 1.26 in
```

## Height
- clear ceiling: ~10 ft ASSUMPTION
- overhead water/electrical service zone: ~8–9.5 ft
- no milk pipe at floor level
- no unprotected electrical item below splash level

## Drawing colors
- milk pipe: blue
- potable cold water: cyan
- hot water: red
- sanitary wastewater: brown
- electrical/data: dark blue
- refrigeration: purple
- gas: absent
