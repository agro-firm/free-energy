# Generator + Electrical — Engineering Math Workbook

## 1. Room area
```
12×14=168 ft²
168×0.09290304=15.6077 m²
```

## 2. Room volume
```
168×10=1,680 ft³
=47.57 m³
```

## 3. Biogas energy
Planning methane fraction:
```
0.60
```

Methane energy:
```
9.97 kWh/m³
```

Biogas thermal:
```
0.60×9.97=5.982 kWh_th/m³
```

At 30% electrical efficiency:
```
5.982×0.30=1.7946 kWh_e/m³
```

## 4. Daily generation
Low gas:
```
8.10×1.7946=14.536 kWh/day
```

High gas:
```
9.18×1.7946=16.474 kWh/day
```

## 5. Gas at 4 kW
```
4/1.7946
=2.229 m³/h
```

Runtime:
```
8.10/2.229=3.63 h/day
9.18/2.229=4.12 h/day
```

## 6. Gas at full 5 kW
```
5/1.7946
=2.786 m³/h
```

This confirms Section 10's 3 m³/h design flow.

## 7. Generator current
At 230 V single phase:

Rated:
```
I=5000/230
=21.74 A
```

Normal:
```
I=4000/230
=17.39 A
```

Concept:
- 32 A 2-pole generator breaker
- 40–63 A ATS hardware with proper 32 A generator-side protection

## 8. Cable voltage drop
Concept:
- copper 6 mm²
- resistance ~3.08 Ω/km at 20°C
- 20 m one-way run
- 40 m loop =0.04 km

Loop resistance:
```
3.08×0.04
=0.1232 Ω
```

At rated current:
```
ΔV=21.74×0.1232
=2.68 V
```

Percentage:
```
2.68/230×100
=1.16%
```

At 4 kW:
```
17.39×0.1232
=2.14 V
=0.93%
```

Allow ~20% higher conductor resistance when hot:
```
rated drop≈1.39%
```

This is acceptable as a planning result, but final ampacity, cable method, derating, fault current and run length require electrical design.

## 9. Room heat
At 4 kW and 30% efficiency:
```
fuel thermal=4/0.30
=13.33 kW
```

Rejected heat:
```
13.33-4
=9.33 kW
```

Assume 35% of rejected heat remains as room sensible heat after exhaust/cooling discharge:
```
9.33×0.35
=3.27 kW
```

## 10. Ventilation airflow
Using:
- air density 1.2 kg/m³
- Cp 1.005 kJ/kg·K
- allowed ΔT 8°C

```
Qv=3.27/(1.2×1.005×8)
=0.339 m³/s
```

```
0.339×3600
=1,220 m³/h
```

Add 25%:
```
≈1,525 m³/h
```

Design concept:
```
1,500–2,000 m³/h
```

## 11. Air changes
At 1,500 m³/h:
```
1500/47.57
=31.5 ACH
```

At 2,000:
```
42.0 ACH
```

## 12. Intake louver
At 1,500 m³/h:
```
0.4167 m³/s
```

At max face velocity 2.5 m/s:
```
free area=0.4167/2.5
=0.1667 m²
```

If louver free-area ratio 50%:
```
gross≈0.333 m²
≈3.59 ft²
```

A 24×24 in gross louver is about 4 ft² and is a reasonable planning minimum.

## 13. Combustion air
At 2.229 m³/h biogas and 60% CH₄:
```
CH4=1.337 m³/h
```

Stoichiometric air:
```
1.337×9.52
=12.73 m³/h
```

At 20% excess:
```
≈15.3 m³/h
```

This is small relative to room cooling ventilation, but still included in final vendor airflow.

## 14. Cost checkpoint
Base subtotal:
```
Tk 1,864,600
```

15% contingency:
```
Tk 279,690
```

Base total:
```
Tk 2,144,290
≈Tk 21.44 lakh
```
