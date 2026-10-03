# Rooftop Solar — Engineering Math Workbook

## 1. DC size
```
24×625 W
=15,000 W
=15.0 kWp
```

## 2. Roof area
```
≈124.223 m²
```

## 3. Module area
One:
```
2.382×1.134
=2.7012 m²
```

Total:
```
24×2.7012
=64.8285 m²
```

Coverage:
```
64.8285/124.223
=52.19%
```

## 4. Module weight
One:
```
32.8 kg
```

Total:
```
24×32.8
=787.2 kg
```

Average module-only load over full roof:
```
787.2/124.223
=6.34 kg/m²
```

Mounting/cables add load; structural engineer checks actual point/uplift loads.

## 5. String Vmp
```
12×41.4
=496.8 V
```

## 6. String Voc
```
12×48.6
=583.2 V
```

## 7. Cold Voc at 0°C
Voc coefficient:
```
-0.25%/°C
```

25°C below STC:
```
583.2×(1+0.0025×25)
=619.65 V
```

Below a 1,100 V inverter max.

## 8. String current
```
Imp≈15.11 A
Isc≈16.14 A
```

One string per MPPT avoids parallel-string current increase.

## 9. AC current
15 kW at 400 V, 3-phase:
```
I=15000/(sqrt(3)×400)
≈21.65 A
```

Concept AC breaker:
- 32 A 4P, subject to inverter/manual/utility.

## 10. AC feeder voltage drop
6 mm² Cu, 30 m one-way:
```
R≈3.08 Ω/km
ΔV≈sqrt(3)×21.65×3.08×0.03
≈3.47 V
```

```
3.47/400×100
≈0.87%
```

## 11. DC cable drop
6 mm² Cu, 30 m one-way /60 m loop:
```
ΔV≈15.11×3.08×0.06
≈2.79 V
```

```
2.79/496.8×100
≈0.56%
```

## 12. Yield
Planning specific yield:
```
3.89 kWh/kWp/day
```

Daily:
```
15×3.89
=58.35 kWh/day
```

Annual:
```
58.35×365
=21,297.75 kWh/year
≈21.30 MWh/year
```

## 13. Cost checkpoint
Base subtotal:
```
Tk1,271,000
```

12% contingency:
```
Tk152,520
```

Base:
```
Tk1,423,520
≈Tk14.24 lakh
```
