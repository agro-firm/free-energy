# Cow Shed — Engineering Math Workbook

This file follows the project's math-solver format:

**Given → Unknown → Assumptions → Formula → Unit substitution → Exact result → Design result → Margin → Verification**

## 1. Footprint

### Given
- L = 48 ft
- W = 26 ft

### Unknown
Floor area.

### Formula
```
A = L × W
```

### Calculation
```
A = 48 × 26 = 1,248 ft²
```

Metric:
```
1,248 × 0.09290304 = 115.94299392 m²
```

### Design result
**1,248 ft² ≈ 115.94 m²**

### Verification
FIXED project baseline.

---

## 2. Stall-run length

### Given
- 10 cows per row
- 40 ft active stall run

### Formula
```
module width = 40 / 10
```

### Calculation
```
40 / 10 = 4 ft/cow module
```

### Design result
**4 ft planning module per cow along row**

### Verification
ASSUMPTION — final livestock specialist must verify against actual breed and restraint system.

---

## 3. Width balance

```
3 + 5.5 + 1.5 + 6 + 1.5 + 5.5 + 3
= 26 ft
```

Result: **PASS**.

---

## 4. Area balance

Dirty strips:
```
2 × 3 × 48 = 288 ft²
```

Cow platforms:
```
2 × 5.5 × 40 = 440 ft²
```

Mangers:
```
2 × 1.5 × 40 = 120 ft²
```

Central feed alley:
```
6 × 48 = 288 ft²
```

Subtotal:
```
288 + 440 + 120 + 288 = 1,136 ft²
```

Residual end-cross areas:
```
1,248 - 1,136 = 112 ft²
```

Check:
```
1,136 + 112 = 1,248 ft²
```

Result: **PASS**.

---

## 5. Roof angle

### Given
- eave = 12 ft
- ridge = 17 ft
- half span = 13 ft

### Calculation
```
rise = 17 - 12 = 5 ft
pitch = 5 / 13 = 0.384615
angle = arctan(0.384615)
angle ≈ 21.04°
```

### Design result
**~21° concept roof slope**

### Verification
ASSUMPTION — structural/roofing engineer may revise.

---

## 6. Roof area allowance

Approximate no-overhang sloped area:
```
A_roof = 1,248 / cos(21.04°)
≈ 1,337.13 ft²
```

Planning allowance with 10%:
```
1,337.13 × 1.10
≈ 1,470.84 ft²
```

Design quantity for early budgeting: **~1,471 ft² roofing allowance**.

---

## 7. Internal air volume

Rectangular body:
```
1,248 × 12 = 14,976 ft³
```

Gable:
```
0.5 × 26 × 5 × 48 = 3,120 ft³
```

Total:
```
18,096 ft³
```

Metric:
```
18,096 × 0.028316846592
≈ 512.42 m³
```

Design result: **~512 m³ internal geometric air volume** before deducting structure/equipment.

---

## 8. Cow drinking-water baseline

### Given
Planning assumption = 80 L/cow/day.

```
20 × 80 = 1,600 L/day
```

This is a planning input, not a guaranteed actual demand.

---

## 9. Concept peak shed-water flow

Assume 25% of daily drinking water is consumed over a 2-hour peak:

```
0.25 × 1,600 = 400 L
400 / 120 min = 3.33 L/min
```

Add one 10 L/min wash hose:
```
3.33 + 10 = 13.33 L/min
```

Planning rounded design flow:
**~15 L/min**

For an approximate 25 mm internal-diameter header:
```
Q = 15 L/min = 0.00025 m³/s
A = π(0.025²)/4 ≈ 0.000491 m²
v = Q/A ≈ 0.51 m/s
```

This suggests a nominal 1-inch-class header can be a reasonable concept, but the final hydraulic design must account for real pipe ID, pressure, simultaneous outlets and distance.

---

## 10. Concept floor cross fall

If cow platform fall = 1.5% over 5.5 ft:

```
fall = 5.5 × 0.015
= 0.0825 ft
= 0.99 in
```

Result: **about 1 inch fall** across the platform.

ASSUMPTION only.

---

## 11. Concept longitudinal dirty-lane fall

If 1% over 48 ft:
```
48 × 0.01 = 0.48 ft
0.48 × 12 = 5.76 in
```

Result: **5.76 in total fall**.

This must be checked against scraper requirements. A powered scraper may require a flatter lane.

---

## 12. Planning electrical connected load

Concept loads:
- four circulation fans: 4 × 0.25 kW = 1.00 kW
- twelve LED fixtures: 12 × 0.018 = 0.216 kW
- two scraper drives allowance: 2 × 1.1 = 2.20 kW
- optional cow brush: 0.10 kW

Connected:
```
1.00 + 0.216 + 2.20 + 0.10
= 3.516 kW
```

If scraper drives are interlocked and not simultaneous, an indicative demand can be lower:
```
1.00 + 0.216 + 1.10 + 0.10
= 2.416 kW
```

Final feeder, breaker, motor-starting current, voltage drop and protection are ELECTRICAL-ENGINEER/VENDOR calculations.

---

## 13. Cost checkpoint

Base planning cost from [COST.md](COST.md):
```
base subtotal = Tk 3,374,400
10% contingency = Tk 337,440
base total = Tk 3,711,840
```

```
Tk 3,711,840 / 100,000 = 37.1184 lakh
```

Design planning total: **~Tk 37.1 lakh for Section 01 only**.

---

## 14. Calculation status table

| Calculation | Status |
|---|---|
| Footprint | FIXED / PASS |
| Width zoning | ASSUMPTION / mathematically balanced |
| Stall module | ASSUMPTION |
| Roof slope | ASSUMPTION |
| Roof area | CALCULATED from assumption |
| Water flow | ASSUMPTION + CALCULATED |
| Drainage slopes | ASSUMPTION |
| Electrical load | ASSUMPTION |
| Structural members | NOT CALCULATED — engineer required |
| Foundation | NOT CALCULATED — soil/engineer required |
| Solar structural load | NOT CALCULATED here — Section 15/vendor/engineer |
