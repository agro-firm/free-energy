# Water Utility — P&ID Concept

```text
SOURCE
  |
  v
GT-701 8m³
  |
 strainer
  |
 +----P-701A----+
 |              |
 +----P-701B----+
        |
     PT-701
        |
     FM-701
        |
   PRESSURE HEADER
   /    |     |    \
 Cow   Milk  S07   Other
        |
       branch
        |
      OHT-701 2m³
        |
   gravity bypass
        +------> priority drinking/essential
```

Interlocks:
- GT low-low → stop pumps
- OHT low → refill request
- OHT high → stop fill
- duty fault → standby start
- high pressure → stop
- no flow while pump runs → alarm
