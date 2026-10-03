# Fertilizer Processing — P&ID Concept

## Tags
- BT-601 buffer tank
- LIT-601 buffer level
- P-601 feed pump
- SP-601 screw press
- LT-601 liquid tank
- LIT-602 liquid tank level
- P-602 liquid transfer pump
- DR-601 leachate/process drain
- CP-601 control panel

## Flow
```text
Section 08
   |
   v
 BT-601
   |
 P-601
   |
 SP-601
 /     \
Cake   Liquid
 |       |
 v       v
Curing  LT-601
 |       |
Bag     P-602
 |       |
Dispatch Field/Transport
```

## Interlocks
- BT low → stop P-601
- LT high-high → stop P-601/SP-601
- SP overload → stop P-601
- drain/leak alarm if installed → stop process as needed

## Drainage
Leachate/wash → DR-601 → LT-601/dirty collection.
No stormwater interconnection.
