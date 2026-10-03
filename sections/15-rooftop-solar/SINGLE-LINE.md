# Rooftop Solar — Electrical Single-Line

```text
24×625 W MODULES
   |
   +-- String A 12 modules --> MPPT1
   |
   +-- String B 12 modules --> MPPT2
                               |
                           INV-901 15kW
                               |
                         AC isolator/SPD
                               |
                          Solar ACDB
                               |
                           FARM MDB
                               |
                        Utility / NEM meter
```

Generator remains separate:
```text
Biogas Generator → ATS → Essential Load Board
```

No baseline connection allows grid-tied inverter to backfeed generator island.
