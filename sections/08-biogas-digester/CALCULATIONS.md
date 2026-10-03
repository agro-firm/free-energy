# Biogas Digester — Engineering Math Workbook

## 1. Compound area
```
16×20 = 320 ft²
320×0.09290304 = 29.729 m²
```

## 2. Minimum HRT volume
```
0.54 m³/day ×30 days
=16.2 m³
```

## 3. Selected working HRT
```
20/0.54
=37.037 days
```

Design result:
**~37-day target HRT**.

## 4. Cylinder cross-sectional area
```
D=2.8 m
r=1.4 m
A=πr²
=π×1.4²
≈6.1575 m²
```

## 5. Total internal height
```
H=25/6.1575
≈4.060 m
```

## 6. Working liquid height
```
20/6.1575
≈3.248 m
```

## 7. Minimum 30-day liquid height
```
16.2/6.1575
≈2.631 m
```

## 8. Headspace
```
25-20
=5 m³
```

Depth:
```
5/6.1575
≈0.812 m
```

## 9. Volume reserve above 30-day minimum
```
20-16.2
=3.8 m³
```

```
3.8/16.2×100
≈23.46%
```

## 10. Total-solids concentration
Fresh-dung TS assumption:
```
270×0.19
=51.3 kg TS/day
```

Diluted slurry:
```
270 kg dung +270 kg water
≈540 kg/day
```

```
51.3/540×100
≈9.5% TS
```

## 11. Volatile-solids loading
Assume VS=80% TS:
```
51.3×0.80
=41.04 kg VS/day
```

At 20 m³:
```
41.04/20
=2.052 kg VS/m³·day
```

## 12. Gas yield
Low:
```
270×0.030
=8.10 m³/day
```

Good operation:
```
270×0.034
=9.18 m³/day
```

## 13. Daily digestate displacement
At steady liquid level:
```
digestate out ≈ slurry in
≈0.54 m³/day
```

Monthly:
```
0.54×30
=16.2 m³/month
```

## 14. Raw-gas outlet sizing check
Assume design peak transfer from digester toward holder:
```
2 m³/h
=0.0005556 m³/s
```

40 mm internal-diameter planning pipe:
```
A=π×0.04²/4
≈0.001257 m²
```

Velocity:
```
0.0005556/0.001257
≈0.442 m/s
```

DN40 / 1.5-inch class is a reasonable low-pressure planning concept, subject to pressure-loss/condensate/vendor review.

## 15. RCC quantity concept
Assume for estimating only:
- internal D=2.8 m
- external D=3.2 m
- wall height=4.06 m
- base D=3.4 m, thickness=0.25 m
- roof D=3.2 m, thickness=0.15 m

Cylinder wall:
```
π/4×(3.2²-2.8²)×4.06
≈7.65 m³
```

Base:
```
π×1.7²×0.25
≈2.27 m³
```

Roof:
```
π×1.6²×0.15
≈1.21 m³
```

Concept total RCC:
```
≈11.13 m³
```

This is **not** a structural design quantity.

## 16. Public civil benchmark
Bangladesh PWD Schedule of Rates provides official chapters for excavation, RCC, steel and related civil works:
https://ss.pwd.gov.bd/sor/sordownload/1

Historical/public PWD RCC examples are roughly in the Tk14,000–16,000/m³ range for concrete alone depending grade/region, excluding important items such as reinforcement/formwork in some entries. The project therefore uses a much higher all-in installed allowance in COST.md.

## 17. Cost checkpoint
Base subtotal:
```
Tk 2,065,000
```

20% contingency:
```
2,065,000×0.20
=Tk 413,000
```

Base total:
```
Tk 2,478,000
≈Tk 24.78 lakh
```
