# Truck / Service Lane — Diagram Pack

## Longitudinal
```text
FRONT
0       10              35              60     70              95 ft
| ENTRY |   MILK 25 ft  |   FEED 25 ft  |CLEAR| REAR/UTILITY 25 |
└──────────────────────────────────────────────────────────────────┘
REAR
```

## Cross section
```text
BUILDING SIDE                                        OUTER DRAIN
X=0                                                     X=14
|<--- painted worker/loading zone --->| truck | clearance |
HIGH --------------------------------------------------- LOW
                 1.5% crossfall
```

## Movement
```mermaid
flowchart LR
    Road --> Gate
    Gate --> Milk
    Milk --> Feed
    Feed --> Rear
    Rear --> Exit[Forward Exit Preferred]
```

## Drainage
```text
buildings/loading side →→ 1.5% →→ outer covered drain
```
