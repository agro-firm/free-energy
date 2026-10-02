# Waste Receiving + Mixing — Engineering Math Workbook

## 1. Area
```
10 × 14 = 140 ft²
140 × 0.09290304 = 13.0064 m²
```

## 2. Fresh dung
```
20 cows × 15 kg/cow/day
= 300 kg/day
```

Collected at 90%:
```
300 × 0.90
= 270 kg/day
```

## 3. Per batch dung
Four batches/day:
```
270 / 4
= 67.5 kg/batch
```

## 4. Water
At 1:1 dung-to-water planning:
```
270 L/day
```

Per batch:
```
270 / 4
= 67.5 L
```

## 5. Slurry
Approximate daily:
```
270 kg dung + 270 kg water
≈540 kg/day
```

At ~1000 kg/m³ planning density:
```
540 / 1000
≈0.54 m³/day
```

Per batch:
```
0.54 / 4
= 0.135 m³
=135 L
```

## 6. Receiving sump
3×3×3 ft:
```
27 ft³ × 0.0283168
=0.7646 m³ gross
```

At 0.60 m³ working:
```
0.60 / 0.27 ≈2.22
```
times the approximate daily undiluted manure volume if density ~1000 kg/m³.

## 7. Mixing tank
Gross:
```
0.50 m³
```

Working:
```
0.35 m³
```

Relative to one 0.135 m³ batch:
```
0.35 / 0.135
=2.59 batch-volumes
```

This provides mixing/headspace margin.

## 8. Emergency sump
3.5×3.5×3 ft:
```
36.75 ft³ ×0.0283168
=1.0405 m³ gross
```

Working:
```
≈0.80 m³
```

Emergency capacity:
```
0.80 / 0.54
=1.48 days of design slurry
```

## 9. Water dosing rate
If 67.5 L must be added in 3 minutes:
```
67.5 / 3
=22.5 L/min
```

A 25 mm / 1-inch line is a reasonable planning concept if supply pressure supports it; hydraulic sizing is ENGINEER/VENDOR.

## 10. Feed-pump target rate
If 135 L batch is pumped in 5 minutes:
```
135 / 5
=27 L/min
```

If in 3 minutes:
```
45 L/min
```

Design pump point should therefore consider roughly **30–50 L/min** plus actual head, solids and viscosity.

## 11. Pipe velocity check — 75 mm concept
At 45 L/min:
```
Q = 45 L/min
=0.00075 m³/s
```

75 mm ID planning:
```
A = π×0.075²/4
≈0.004418 m²
```

Velocity:
```
0.00075 / 0.004418
≈0.17 m/s
```

This is low; settling risk must be reviewed. Vendor may select smaller pipe, higher pump rate or intermittent flush based on actual manure rheology.

**Therefore 75 mm is a blockage-avoidance concept, not a finalized hydraulic size.**

## 12. Mixer energy
Assume 0.75 kW mixer × 10 min/batch ×4:
```
0.75 × (10/60) ×4
=0.50 kWh/day
```

## 13. Pump energy
Assume two 0.75 kW pumps, each 5 min/batch ×4:
```
2 ×0.75×(5/60)×4
=0.50 kWh/day
```

Controls/sensors allowance:
```
~0.2 kWh/day
```

Planning Section 07 electricity:
```
≈1.2 kWh/day
```

## 14. Public equipment price checks — 2026
Bangladesh examples:
- 0.5 HP sewage pump ~Tk7,966
- 1 HP drainage pump ~Tk9,800
- 2-inch electromagnetic flow meter ~Tk65,000
- water float/level sensors ~Tk199–950 for simple water service
- 1-inch solenoid valve ~Tk2,085–2,149

Manure-duty equipment requires stronger industrial specification, so COST.md uses higher vendor allowances.

## 15. Cost checkpoint
Base subtotal:
```
Tk 1,222,000
```

15% contingency:
```
1,222,000×0.15
=Tk 183,300
```

Base total:
```
Tk 1,405,300
≈Tk 14.05 lakh
```
