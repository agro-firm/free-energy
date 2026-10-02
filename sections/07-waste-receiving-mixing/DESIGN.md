# Waste Receiving + Mixing — Functional Design

## 1. Process philosophy
The section converts variable incoming manure into a controlled, homogeneous slurry batch that the digester can accept reliably.

The design avoids feeding raw, unmixed, debris-laden manure directly to Section 08.

## 2. Receiving
Incoming manure first passes a removable coarse screen.

Screen goals:
- stop rope/plastic/bedding
- reduce pump blockage
- protect mixer and flow meter
- make foreign-material inspection easy

The screen must be serviceable without entering the sump.

## 3. Receiving sump
RS-101 buffers the scraper/gutter inflow.

Concept:
- gross ~0.765 m³
- working ~0.60 m³
- high, high-high and low-level sensing
- covered
- transfer pump P-101
- emergency diversion to ES-101

## 4. Weight-based dung batching
MT-101 sits on load cells.

For each feed cycle:
```
target dung mass ≈67.5 kg
```

P-101 transfers dung from RS-101 until load-cell mass reaches the batch target.

This is preferred over pump-time-only dosing because manure density/solids can vary.

## 5. Water dosing
Current planning ratio:
```
1 kg dung : 1 L water
```

Per batch:
```
67.5 kg dung + 67.5 L water
```

Water is measured by water meter/flow transmitter and controlled by solenoid valve.

The ratio is an ASSUMPTION and must be adjusted to actual total-solids/rheology and digester vendor requirements.

## 6. Mixing
Top-entry or side-entry low-speed mixer:
- planning motor ~0.75 kW / 1 HP
- mix time 5–10 min ASSUMPTION
- mixer permissive only when adequate level exists
- guarded coupling
- overload protection

Goal: pumpable homogeneous slurry, not high-shear grinding.

## 7. Feed to digester
After mixing:
- confirm Section 08 ready
- confirm digester not high-high
- start P-102
- measure slurry volume through electromagnetic meter
- target ~0.135 m³/batch
- stop on target, low tank level or fault

## 8. Emergency holding
ES-101 provides temporary containment when:
- digester is unavailable
- feed pump fails
- receiving sump high-high
- line is blocked

Working volume:
```
0.80 m³
```

Relative to daily slurry:
```
0.80 / 0.54 = 1.48 days
```

This is emergency buffer, not routine storage.

## 9. Process timing
Four feed windows/day, approximately 6 hours apart, are a planning concept.

PLC should permit delayed feeding if:
- insufficient manure
- digester high level
- maintenance mode
- pump/flow-meter fault

## 10. Cleaning
Preferred:
- remove solids manually from screen
- use minimal wash water
- periodic line flush only as process permits
- record flush water because it changes digester dilution

## 11. No hidden bypass
No overflow is permitted to:
- stormwater
- public drain
- service lane
- clean water system

All process overflows go to contained dirty/emergency storage.
