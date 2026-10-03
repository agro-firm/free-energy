# Section 21 Master Diagrams

## Delivery lifecycle
```mermaid
flowchart LR
    IFC --> Mobilize
    Mobilize --> Civil
    Civil --> Process
    Process --> MEP
    MEP --> PreCom[Precommission]
    PreCom --> Start[Startup]
    Start --> Trial[Integrated Trial]
    Trial --> Handover
```

## Quality
```
Approved Drawing + Material + Method + ITP
                ↓
              WORK
                ↓
             IR/Test
                ↓
       Accept / NCR / Rework
                ↓
             As-Built
```

## Schedule
```
W1–8 underground
W5–18 structures
W15–30 equipment/MEP
W28–38 commissioning
W38–40 trial/handover
```
