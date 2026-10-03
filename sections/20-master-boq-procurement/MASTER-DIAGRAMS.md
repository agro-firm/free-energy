# Procurement / Cost Control Diagrams

## Money flow
```mermaid
flowchart LR
    Budget[CBS Budget] --> RFQ
    RFQ --> TBE[Technical Evaluation]
    TBE --> CBE[Normalized Commercial]
    CBE --> Award
    Award --> Commit[Committed Cost]
    Commit --> Invoice
    Invoice --> Paid
    Award --> Forecast[FAC]
```

## Scope
```
SECTION BUDGETS → MASTER BOQ → PPK PACKAGES → PO/CONTRACTS
```

## Dedup
```
Duplicate candidate → ownership decision → retained quote → exact credit → updated forecast
```
