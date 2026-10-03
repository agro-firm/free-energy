# Gas Treatment — Engineering Math Workbook

## 1. Zone area
```
8×10=80 ft²
80×0.09290304=7.4322 m²
```

## 2. Design flow
Generator demand:
```
≈2.23 m³/h
```

Peak treatment design:
```
3.0 m³/h
```

Margin:
```
3/2.23=1.345
```
≈34.5% flow margin.

## 3. H₂S mass — base case
High daily gas:
```
9.18 m³/day
```

Base H₂S:
```
2,000 ppm=0.002 volume fraction
```

H₂S density at ~25°C/1 atm:
```
≈1.394 kg/m³
```

```
9.18×0.002×1.394
=0.02559 kg/day
=25.59 g/day
```

## 4. H₂S sensitivity
At 1,000 ppm:
```
≈12.80 g/day
```

At 3,000 ppm:
```
≈38.39 g/day
```

## 5. Removal to 100 ppm
At 2,000 ppm inlet:
```
removal fraction=(2000-100)/2000
=0.95
```

```
25.59×0.95
=24.31 g/day removed
```

## 6. Media capacity
Planning capacity:
```
0.10 kg H₂S/kg media
```

One 25 kg bed:
```
25×0.10
=2.5 kg H₂S theoretical
```

Theoretical life at base:
```
2.5/0.02431
=102.8 days
```

At conservative 50% usable capacity:
```
≈51.4 days
```

## 7. High H₂S sensitivity
At 3,000 ppm inlet and 100 ppm outlet:
```
38.39×(2900/3000)
≈37.11 g/day removed
```

Theoretical:
```
2.5/0.03711
≈67.4 days
```

At 50% usable:
```
≈33.7 days
```

Therefore actual breakthrough monitoring is mandatory.

## 8. Media bed volume
Assume bulk density:
```
500 kg/m³
```

For 25 kg:
```
25/500
=0.05 m³
=50 L
```

## 9. Vessel bed height
Assume internal D:
```
0.30 m
```

Area:
```
π×0.30²/4
=0.07069 m²
```

Bed height:
```
0.05/0.07069
=0.707 m
```

## 10. Superficial velocity
At 3 m³/h:
```
Q=0.0008333 m³/s
```

```
v=0.0008333/0.07069
=0.0118 m/s
```

## 11. Empty-bed contact time
```
EBCT=0.05/0.0008333
≈60 s
```

This is generous for a small system and helps keep pressure drop low; media vendor must still approve.

## 12. DN40 velocity
```
Q=3 m³/h=0.0008333 m³/s
A=π×0.04²/4
=0.001257 m²
```

```
v≈0.663 m/s
```

## 13. Booster power
Planning:
```
0.37 kW
```

Assume generator operates 4 h/day:
```
0.37×4
=1.48 kWh/day
```

Sensors/controls allowance:
```
≈0.2 kWh/day
```

Treatment electrical consumption:
```
≈1.7 kWh/day
```

Actual blower duty depends on required pressure rise.

## 14. Public Bangladesh market references
- multi-gas H₂S/LEL/O₂/CO detector: about Tk14,500–25,000 in October 2026 listings.
- generic coconut-shell activated carbon: about Tk170/kg retail, but this is **not** equivalent to impregnated H₂S media.
- general electromagnetic liquid flow meters: Tk45,000–65,000; these are not suitable for gas and only illustrate instrumentation cost scale.

## 15. Cost checkpoint
Base subtotal:
```
Tk 1,280,000
```

20% contingency:
```
1,280,000×0.20
=Tk 256,000
```

Base total:
```
Tk 1,536,000
≈Tk 15.36 lakh
```
