# Gas Treatment — P&ID Concept

## Tags
KO-401 inlet knockout
V-401A lead H₂S vessel
V-401B lag H₂S vessel
MS-401 moisture separator
PF-401 particulate filter
FIT-401 gas meter
AIT-401 H₂S outlet analyzer
B-401 booster
PCV-401 generator pressure regulator
PIT-401/PIT-402 pressure
XV-401/XV-402 isolation
GD-401 area gas detector

## Normal series
```text
Section 09
   |
 XV-401
   |
 PIT-401
   |
 KO-401 ---- closed condensate drain
   |
 SP-401A
   |
 V-401A  LEAD
   |
 SP-401B
   |
 V-401B  LAG
   |
 MS-401 ---- closed condensate drain
   |
 PF-401
   |
 AIT-401 / SP-401C
   |
 FIT-401
   |
 B-401
   |
 PIT-402
   |
 PCV-401
   |
 XV-402
   |
Section 11 Generator
```

## Lead/lag crossover
Valve manifold may reverse A/B order, but **no untreated bypass to Section 11 is provided**.

## Safety interfaces
- Section 09 low holder → stop B-401
- H₂S high → inhibit Section 11
- gas detector high → shut down/isolate
- condensate high → inhibit flow if carryover risk
- Section 11 generator ready required before gas demand
