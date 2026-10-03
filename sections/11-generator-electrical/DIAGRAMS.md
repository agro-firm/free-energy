# Generator + Electrical — Diagram Pack

## Room plan
```text
NORTH: HOT-AIR + ENGINE EXHAUST OUT
┌────3 ft────┬──────6 ft──────┬────5 ft────┐
│ GAS/SERVICE│   5 kW GENSET   │ ATS / ELP  │
│            │                 │ PANELS     │ 12 ft
│            │                 │            │
└────── INTAKE LOUVER ──────── DOOR ───────┘
SOUTH
```

## Gas-energy
```mermaid
flowchart LR
    S09[Gas Holder] --> S10[Gas Treatment]
    S10 --> GEN[5 kW Generator]
    GEN --> ATS
    ATS --> ELP[Essential Load Board]
```

## Electrical
```mermaid
flowchart LR
    Normal[Grid/Solar Main Bus] --> ATS
    Gen[Biogas Generator] --> ATS
    ATS --> ELP
    ELP --> T1[Tier 1]
    ELP --> T2[Tier 2]
```

## Ventilation
```text
LOW SOUTH COOL AIR ---> GENERATOR ---> HIGH NORTH HOT AIR
                                ----> ENGINE EXHAUST SEPARATE PIPE
```

## Colors
treated gas light green
electric dark blue
control purple
cool air cyan
hot air magenta
exhaust orange/red
earth yellow-green
