# Cow Yard — Engineering Math Workbook

## 1. Total area
Given 18 ft × 28 ft:
```
A = 18 × 28 = 504 ft²
504 × 0.09290304 = 46.8231 m²
```
Result: **504 ft² = 46.82 m²**.

## 2. Density if 20 cows use the whole yard
```
46.8231 / 20 = 2.3412 m²/cow
```
This is too tight for the project's intended exercise/holding use.

## 3. Active zone
```
18 × 24 = 432 ft²
432 × 0.09290304 = 40.1341 m²
```

For 10 cows:
```
40.1341 / 10 = 4.0134 m²/cow
```
Design result: **10 cows per rotation**.

## 4. Shade ratio
```
shade = 12 × 18 = 216 ft²
216 / 504 = 42.86%
216 / 432 = 50%
```

## 5. Service strip
```
4 × 18 = 72 ft²
72 × 0.09290304 = 6.6890 m²
```

## 6. Fence perimeter
```
P = 2(18+28) = 92 ft
```
If 5 ft high:
```
mesh face area = 92 × 5 = 460 ft²
```
Actual mesh quantity is reduced/increased by gates, overlaps and post details.

## 7. Floor slope
At 1.25% over 28 ft:
```
28 × 0.0125 = 0.35 ft
0.35 × 12 = 4.2 in
```
Result: **4.2 in conceptual total fall**.

## 8. Pavement volume
Assume 100 mm (0.10 m) concrete slab:
```
46.8231 × 0.10 = 4.6823 m³
```

LGED Schedule of Rates 2025 lists Zone-D RCC pavement rates around Tk 15,958/m³ for a 20 MPa crushed-stone pavement item. Using that as a historical/public benchmark:
```
4.6823 × 15,958.34 ≈ Tk 74,717
```
This excludes all project-specific subbase, reinforcement, finish, drainage, 2026 escalation and contractor conditions; COST.md therefore uses a higher installed planning allowance.

## 9. Water concept
10 cows × 80 L/day full-day drinking basis:
```
10 × 80 = 800 L/day
```
If 15% occurs during a 1-hour yard session:
```
800 × 0.15 = 120 L/hour
120 / 60 = 2 L/min
```
Add one 10 L/min wash hose:
```
2 + 10 = 12 L/min
```
Rounded planning flow: **15 L/min**.

## 10. Lighting load
Two 30 W LED fixtures:
```
2 × 30 = 60 W = 0.06 kW
```
One 10 W camera:
```
0.01 kW
```
Total concept connected load:
```
0.07 kW
```

## 11. Cost checkpoint
Base subtotal in COST.md:
```
Tk 476,000
```
10% contingency:
```
Tk 47,600
```
Base total:
```
Tk 523,600 = 5.236 lakh
```
