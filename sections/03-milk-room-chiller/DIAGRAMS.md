# Milk Room + Chiller — Diagram Pack

## Plan
```text
NORTH — CLEAN MILKING / SHED SIDE
┌──────────────┬────────────────┬───────────┐
│ RECEIVE/TEST │                │ CLEAN     │
│ 6×6          │   CHILLER      │ INGRESS   │
├──────────────┤   7×14         │ 5×6       │
│ WASH / CIP   │                ├───────────┤
│ 6×8          │                │ DISPATCH  │
│              │                │ 5×8       │
└──────────────┴────────────────┴──── DOOR ─┘
SOUTH — SERVICE LANE / MILK TRUCK
```

## Milk flow
```mermaid
flowchart LR
    Shed --> Receive --> Filter --> Test --> Chiller --> Truck
```

## Water/CIP
```mermaid
flowchart LR
    Cold[Potable Cold Water] --> Wash
    Hot[Hot Water] --> Wash
    Wash --> CIP[CIP / Cleaning]
    CIP --> Waste[Process Wastewater]
    Waste --> Treatment[Approved Wastewater Route]
```

## Power priority
```text
CRITICAL: chiller → controls → essential pump → lights/ventilation
NON-CRITICAL ON BACKUP: hot-water heater → optional equipment
```

## Utility rule
```text
BLUE milk
CYAN cold water
RED hot water
BROWN wastewater
PURPLE refrigeration
DARK BLUE electrical/data
GREEN GAS = NONE
```
