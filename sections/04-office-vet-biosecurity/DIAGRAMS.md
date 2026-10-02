# Office + Vet + Biosecurity — Diagram Pack

## Plan
```text
WEST / PUBLIC ENTRY                                      EAST / FARM
┌────────────┬───────────────┬────────────────────────────┐
│            │               │ MEDICINE + VACCINE 6×4   │
│ BIOSECURITY│ OFFICE /      ├────────────────────────────┤
│ 4×12       │ MONITOR 5×12  │ VET / AI 6×8             │
│            │               │ sink • bench • LN2 tank  │
└── PUBLIC ──┴───────────────┴──────────── FARM DOOR ────┘
```

## Biosecurity flow
```mermaid
flowchart LR
    Outside --> Footwear --> PPE --> Handwash --> CleanSide
```

## Medicine cold chain
```mermaid
flowchart LR
    Delivery --> Inspect --> Log --> Fridge[2-8°C Fridge]
    Fridge --> Issue --> AnimalRecord
    Logger --> Alarm
```

## Data/security
```mermaid
flowchart LR
    Cameras --> NVR --> Monitor
    NVR --> Router
    FridgeLogger --> Router
    Router --> Remote[Remote Alert / Dashboard]
```

## Critical power
```text
Plant supply
   ↓
Critical circuit
   ├── vaccine fridge
   ├── temperature logger
   ├── NVR/router
   └── emergency light
        ↑
     local UPS bridge
```

## Utility colors
CYAN water
BROWN sanitary drainage
DARK BLUE power/data
PURPLE vaccine cold-chain
MAGENTA CCTV/security
GREEN GAS = NONE
