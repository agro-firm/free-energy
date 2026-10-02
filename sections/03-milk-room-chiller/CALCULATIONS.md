# Milk Room + Chiller — Engineering Math Workbook

## 1. Room area
```
18 × 14 = 252 ft²
252 × 0.09290304 = 23.4116 m²
```

## 2. Milk production basis
Assumptions:
- 20 adult cows
- 70% lactating = 14 cows
- 10 L/cow/day average

```
20 × 0.70 = 14 cows
14 × 10 = 140 L/day
```

Two milkings/day:
```
140 / 2 = 70 L/milking
```

## 3. Chiller capacity
Add 20% operating reserve:
```
140 × 1.20 = 168 L/day design volume
```

300 L tank:
```
300 / 168 = 1.79 design-days capacity
```

500 L tank:
```
500 / 168 = 2.98 design-days capacity
```

Recommendation:
- **300 L minimum** for daily pickup
- **500 L preferred** for extra reserve / alternate-day collection

Milk should not be stored longer simply because tank capacity exists.

## 4. Cooling duty for daily milk
Assume milk specific heat ≈ 3.93 kJ/kg·K.
Cool 140 kg from 35°C to 4°C:
```
ΔT = 31 K
Q = 140 × 3.93 × 31
= 17,056.2 kJ
```

Convert:
```
17,056.2 / 3600 = 4.738 kWh thermal
```

Add 20%:
```
4.738 × 1.20 = 5.686 kWh thermal
```

If removed within 2 hours:
```
5.686 / 2 = 2.843 kW thermal average
```

Vendor must certify actual cooling performance at Bangladesh ambient conditions.

## 5. Washing water planning
Using FAO dairy-housing guidance as planning reference:

Pipeline milking wash twice/day:
- hot: 30 L ×2 = 60 L
- cold: 60 L ×2 = 120 L

Bulk tank wash once/day planning:
- hot: 35 L
- warm: 25 L
- cold: 30 L

Milkroom floor:
```
23.41 m² × 2 L/m²/day
= 46.82 L/day
```

Miscellaneous planning:
- hot 30 L/day
- cold 50 L/day

Totals:
```
hot = 60+35+30 = 125 L/day
warm = 25 L/day
cold = 120+30+46.82+50 = 246.82 L/day
total ≈ 396.82 L/day
```

## 6. Hot-water energy
Heat 125 L from 25°C to 85°C:
```
Q = 125 × 4.186 × 60
= 31,395 kJ
= 8.72 kWh thermal
```

At 85% heater efficiency:
```
8.72 / 0.85 = 10.26 kWh electrical
```

5 kW heater ideal operating time:
```
10.26 / 5 = 2.05 h/day
```

## 7. Ventilation
Room volume:
```
252 ft² × 10 ft = 2,520 ft³
≈ 71.36 m³
```

At 8 ACH:
```
71.36 × 8 = 570.9 m³/h
≈ 336 cfm
```

## 8. Electrical connected load — concept
- chiller compressor/agitator allowance: 1.50 kW
- hot-water heater: 5.00 kW
- milk-transfer pump: 0.75 kW
- CIP/wash pump: 0.55 kW
- lights: 0.108 kW
- ventilation: 0.25 kW
- testing/small refrigeration/data: 0.15 kW

```
total = 8.308 kW
```

Critical backup excluding hot water and nonessential CIP:
```
1.50 + 0.75 + 0.108 + 0.25
= 2.608 kW
```

The 5 kW biogas generator can conceptually support critical milk-room loads, subject to compressor starting-current verification.

## 9. Cost checkpoint
Base subtotal:
```
Tk 1,990,000
```
12% contingency:
```
Tk 238,800
```
Total:
```
Tk 2,228,800 = 22.288 lakh
```
