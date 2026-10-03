# Master Diagrams

## Whole value chain
```mermaid
flowchart LR
    Feed[Feed] --> Cows[01 Cows]
    Cows --> Milk[03 Milk]
    Cows --> Manure[07 Waste]
    Manure --> Digester[08 Digester]
    Digester --> Gas[09 Gas Storage]
    Gas --> Treat[10 Gas Treatment]
    Treat --> Gen[11 Generator]
    Digester --> Fert[12 Fertilizer]
    Solar[15 Solar] --> Power[Plant Electricity]
    Gen --> Power
    Water[13 Water] --> Cows
    Water --> Milk
```

## Logistics
```mermaid
flowchart LR
    Lane[14 Service Lane] --> FeedCanopy[06 Feed Canopy]
    FeedCanopy --> FeedStore[05 Feed Store]
    Lane --> Milk[03 Milk Pickup]
    Lane --> Gen[11 Service]
    Lane --> Fert[12 Fertilizer Dispatch]
```

## Clean-to-dirty progression
```text
FRONT
Public / clean / feed
        ↓
Dairy / milk
        ↓
Waste / slurry
        ↓
Digester
        ↓
Gas / power / fertilizer
REAR
```

## Power
```mermaid
flowchart LR
    Solar[15 Solar] --> MDB[Main MDB]
    Grid[Utility] --> MDB
    MDB --> Loads[Normal Plant Loads]
    Gen[11 Biogas Generator] --> ATS
    Grid --> ATS
    ATS --> ELP[Essential Load Board]
```

## Water
```mermaid
flowchart LR
    Source --> GT[13 Ground Tank 8m3]
    GT --> Pumps[Twin Pumps]
    Pumps --> Header[Pressure Header]
    Header --> OHT[2m3 OHT]
    Header --> Cows
    Header --> Milk
    Header --> Waste
    Header --> Fert
```

## Rule
Detailed local diagrams remain in the relevant section.
