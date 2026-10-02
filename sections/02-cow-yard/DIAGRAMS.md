# Cow Yard — Diagram Pack

## Plan
```text
NORTH
┌──────────────────────────── 28 ft ─────────────────────────────┐
│      SHADED 12×18      │      OPEN 12×18       │ SERVICE 4×18 │
│                        │                        │ trough       │
│   up to 10 cows total across active 24×18 ft   │ dirty drain │
│                        │                        │ hose         │
└──────────── cattle gate / shed connection ────────────────────┘
SOUTH
```

## Area
```
216 + 216 + 72 = 504 ft²
```

## Rotation
```mermaid
flowchart LR
    Shed --> G1[10 cows]
    G1 --> Yard
    Yard --> Shed
    Shed --> G2[10 cows]
    G2 --> Yard
```

## Drainage
```mermaid
flowchart LR
    Open[Open Yard Rain + Manure] --> Dirty[Dirty Linear Drain]
    Dirty --> Waste[Approved Dirty-Water Route]
    Shade[Shade Roof Rain] --> Gutter[Clean Gutter]
    Gutter --> Storm[Clean Stormwater]
```

## Utilities
```text
CYAN       water → trough + wash hose
BROWN      paved floor → dirty drain
LIGHT BLUE canopy roof → clean stormwater
DARK BLUE  lighting/CCTV
GREEN GAS  NONE
```
