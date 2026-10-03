# Section 18 Master Diagrams

## Vertical-design chain
```
SURVEY RL
   ↓
FLOOD / ROAD / OUTFALL
   ↓
PROPOSED SITE GRADING
   ↓
FFL / PROCESS SLABS
   ↓
DRAIN INVERTS
   ↓
FOUNDATION / EXCAVATION
```

## Drainage
```mermaid
flowchart LR
    Roof[Clean roofs] --> Storm[Clean storm system]
    Lane[Service lane] --> Storm
    Storm --> Outfall[Approved outfall]

    Cow[Dirty cow flows] --> Waste[Section 07]
    Fert[Fertilizer leachate] --> Dirty[Contained process]
    Gas[Gas condensate] --> Dirty
```

## IFC gates
```
Survey → Flood → Drainage → Earthwork → Road → Utilities → Safety → Vendor → QA → IFC
```
