# Gas Storage — Engineering Math Workbook

## 1. Zone area
```
10×12
=120 ft²
```

```
120×0.09290304
=11.1484 m²
```

## 2. Nominal holder
```
V=8 m³
```

Equivalent planning envelope:
```
2×2×2
=8 m³
```

Actual flexible shape is vendor-specific.

## 3. Percentage inventory
20%:
```
8×0.20
=1.6 m³
```

30%:
```
8×0.30
=2.4 m³
```

75%:
```
8×0.75
=6.0 m³
```

90%:
```
8×0.90
=7.2 m³
```

95%:
```
8×0.95
=7.6 m³
```

## 4. Usable control swing
From 75% down to 20%:
```
6.0-1.6
=4.4 m³
```

## 5. Generator runtime per swing
Current project generator gas demand:
```
≈2.23 m³/h
```

```
4.4/2.23
=1.973 h
```

Result:
**~1.97 h generator runtime per normal holder swing**.

## 6. Full-holder production coverage
Low gas case:
```
8/8.10
=0.9877 day
=23.70 h
```

Good gas case:
```
8/9.18
=0.8715 day
=20.92 h
```

## 7. Fill time from 20% to 75%
Required:
```
4.4 m³
```

At 8.10 m³/day:
```
4.4/8.10×24
=13.04 h
```

At 9.18 m³/day:
```
4.4/9.18×24
=11.50 h
```

If no gas is consumed, the holder can recover a normal 20→75% swing in roughly **11.5–13 hours**.

## 8. Fill time 20% to 95%
```
7.6-1.6
=6.0 m³
```

At 8.10:
```
6/8.10×24
=17.78 h
```

At 9.18:
```
6/9.18×24
=15.69 h
```

## 9. Gas line velocity
Design raw-gas transfer check:
```
Q=3 m³/h
=0.0008333 m³/s
```

Assume 40 mm ID:
```
A=π×0.04²/4
=0.001257 m²
```

```
v=0.0008333/0.001257
≈0.663 m/s
```

DN40 / 1.5-inch class remains a reasonable low-pressure conceptual line size pending full pressure-drop/condensate calculation.

## 10. Protective frame fit
Zone:
```
3.658×3.048 m
```

Frame:
```
2.4×2.4 m
```

Remaining length:
```
3.658-2.4
=1.258 m
```

Remaining width:
```
3.048-2.4
=0.648 m
```

Routine service is therefore concentrated on the long-side manifold strip rather than requiring full walk-around access.

## 11. Public small-holder market checks
2026 public examples:
- 10 m³ double-layer PVC biogas balloon: about INR 11,000–15,000 membrane-only.
- small gas bags: roughly US$28–38/m³ in some listings.
- 10 m³ PVC/TPU gas bladder: roughly US$200–1,000/unit depending supplier/specification.

These are **not installed project prices**.

## 12. Cost checkpoint
Base subtotal:
```
Tk 815,000
```

20% contingency:
```
815,000×0.20
=Tk 163,000
```

Base total:
```
Tk 978,000
≈Tk 9.78 lakh
```
