# Waste Receiving + Mixing — Diagram Pack

## Plan
```text
WEST / FROM COW SHED                          EAST / TO DIGESTER
┌──────────────┬──────────────────┬──────────────┐
│ SCREEN/GRIT  │                  │ CONTROL      │
│ + RS-101     │ MT-101 + M-101   │ + ES-101     │ 10 ft
│ + P-101      │ P-102 + METERS   │ PLC/PPE      │
└──────────────┴──────────────────┴──────────────┘
     4 ft              6 ft             4 ft
TOTAL LENGTH = 14 ft
```

## Batch mass flow
```mermaid
flowchart LR
    D[270 kg dung/day] --> B[4 batches]
    B --> M[67.5 kg dung/batch]
    W[270 L water/day] --> WB[67.5 L/batch]
    M --> S[Mix]
    WB --> S
    S --> F[~0.135 m³ slurry/batch]
```

## Emergency flow
```mermaid
flowchart LR
    RS[RS-101 High-High] --> ES[ES-101 Emergency Sump]
    ES --> Alarm
    Alarm --> Operator
```

## Control chain
```text
LEVELS → PLC ← LOAD CELLS
          ↑
WATER FLOW/VALVE
          ↑
MIXER/PUMPS
          ↑
SLURRY FLOW
          ↑
DIGESTER READY
```

## Utility colors
BROWN = manure/slurry
CYAN = water
ORANGE = emergency containment
DARK BLUE = power/data
PURPLE = controls
GREY = vent/odor
