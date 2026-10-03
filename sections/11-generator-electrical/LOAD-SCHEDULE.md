# Generator + Electrical — Essential Load Schedule

## Purpose
The 5 kW generator cannot run every farm load simultaneously. This schedule defines priority and sequencing.

## Normal generator operating target
```
≈4.0 kW
```

Maintain margin for:
- motor starting
- transient loads
- voltage/frequency recovery

## Tier 1 — critical/no-shed
| Load | Planning kW |
|---|---:|
| Milk chiller refrigeration | 1.50 |
| Section 10 booster + controls | 0.45 |
| Vaccine fridge + CCTV/router/logger | 0.30 |
| Plant PLC/data/alarms | 0.20 |
| Essential lighting | 0.15 |
| **Tier 1 total** | **2.60 kW** |

## Tier 2 — sequenced
| Load | Planning kW | Rule |
|---|---:|---|
| Water pump | 0.75 | run when milk pump off |
| One cow-shed fan | 0.25 | heat priority |
| Milk transfer pump | 0.75 | temporary; shed water pump if needed |
| Selected process pump | 0.75 | only when bus margin exists |

Example steady set:
```
2.60 +0.75 +0.25
=3.60 kW
```

Leaves:
```
4.00-3.60
=0.40 kW
```
normal operating margin.

## Tier 3 — locked out on generator unless operator-approved
- 5 kW milk-room hot-water heater
- feed mixer
- multiple manure scraper motors
- dehumidifiers
- nonessential office sockets
- battery charging at high rate
- optional heavy workshop loads

## Motor starting
Compressor/pump starting current can be several times running current.
Controls should:
- start loads sequentially
- delay chiller after ATS transfer
- use soft-start/VFD where compatible
- prevent two major motors starting simultaneously

## Emergency mode
If only minimum critical power is required:
```
Tier 1≈2.6 kW
```
giving greater fuel/runtime margin.

## Final rule
Section 13 water-pump and Section 15 inverter selections may change individual load values. Update this file whenever equipment is finalized.
