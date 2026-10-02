# Office + Vet + Biosecurity — Blueprint and XYZ Specification

## Local coordinate system
- origin = southwest floor corner
- X = west→east, 0–15 ft
- Y = south→north, 0–12 ft
- Z = vertical

## Zone geometry
| Zone | X | Y | Size | Area |
|---|---|---|---|---:|
| Biosecurity | 0–4 | 0–12 | 4×12 | 48 ft² |
| Office/monitoring | 4–9 | 0–12 | 5×12 | 60 ft² |
| Vet/AI | 9–15 | 0–8 | 6×8 | 48 ft² |
| Medicine/vaccine | 9–15 | 8–12 | 6×4 | 24 ft² |

## Doors
### Public/biosecurity door
Concept:
```
X = 0
Y ≈ 4–8 ft
width ≈ 3.5 ft
```

### Farm/clean door
Concept:
```
X = 15
Y ≈ 3–6.5 ft
width ≈ 3.5 ft
```

### Medicine-store door
Internal lockable door from office/vet side; final swing selected to avoid blocking refrigerator.

## Equipment coordinates — planning
- change bench: around (1.2, 6)
- PPE locker: along Y=10–12 in biosecurity zone
- handwash: around (3,2)
- office desk: around (6.5,4)
- CCTV/NVR rack: around (5,10)
- filing cabinet: around (8,10)
- vet workbench: around (11.5,3)
- vet sink: around (14,2)
- LN₂ tank position: around (13.5,6.5), ventilated and restrained
- medicine fridge: around (11,10)
- medicine cabinet: around (14,10)

## Height concept
- clear ceiling: ~10 ft ASSUMPTION
- data/electrical tray: 8–9.5 ft
- wall cabinets: keep accessible without unsafe ladders
- CCTV/NVR at secure office height
- vaccine refrigerator floor-mounted

## Wet points
- HW-01 handwash in biosecurity
- VS-01 vet sink
- FD-01 optional local floor drain at biosecurity/wet threshold
- FD-02 optional vet-sink/service drain if final civil design requires

## Color conventions
- potable water cyan
- sanitary drainage brown
- electrical/data dark blue
- vaccine cold-chain purple
- security/CCTV magenta
- gas green = absent
