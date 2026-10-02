# Office + Vet + Biosecurity — Engineering Math Workbook

## 1. Floor area
```
12 × 15 = 180 ft²
180 × 0.09290304 = 16.7225 m²
```

## 2. Space balance
```
Biosecurity = 4 × 12 = 48 ft²
Office = 5 × 12 = 60 ft²
Vet/AI = 6 × 8 = 48 ft²
Medicine = 6 × 4 = 24 ft²
Total = 48+60+48+24 = 180 ft²
```
PASS.

## 3. Volume
At 10 ft clear height:
```
180 × 10 = 1,800 ft³
1,800 × 0.0283168 ≈ 50.97 m³
```

## 4. Ventilation
At 6 ACH:
```
50.97 × 6 = 305.82 m³/h
305.82 / 1.699 ≈ 180 cfm
```
Planning exhaust/fresh-air provision: **200–250 cfm** plus AC, subject to HVAC design.

## 5. Electrical connected load — concept
- 1-ton inverter AC allowance: 1.20 kW
- vaccine fridge: 0.20 kW
- computer: 0.15 kW
- monitor: 0.05 kW
- CCTV/NVR: 0.05 kW
- router/network: 0.02 kW
- printer peak: 0.60 kW
- 4 LED lights: 4×0.018 = 0.072 kW
- vet small equipment allowance: 0.15 kW

```
total = 1.20+0.20+0.15+0.05+0.05+0.02+0.60+0.072+0.15
= 2.492 kW
```

## 6. Critical backup
Critical:
- vaccine fridge 0.20
- NVR 0.05
- router 0.02
- one light 0.018
- temperature/data logger allowance 0.01

```
critical = 0.298 kW
```

Four-hour local autonomy:
```
0.298 × 4 = 1.192 kWh
```

Assume 85% system efficiency:
```
1.192 / 0.85 = 1.402 kWh
```

Planning backup energy: **~1.5–2.0 kWh usable/nominal system depending battery chemistry and design**, plus plant generator/solar backup.

## 7. Refrigerator energy
A public 226 L 2–8°C pharmacy refrigerator example lists 200 W nameplate.

Worst-case nameplate continuous:
```
0.2 × 24 = 4.8 kWh/day
```

Actual cycling energy should be lower and must come from manufacturer data.

## 8. Water
Planning:
- handwash 20 L/day
- vet sink 25 L/day
- floor/entry cleaning 20 L/day
- miscellaneous 15 L/day

```
20+25+20+15 = 80 L/day
```

Design planning demand: **~80 L/day**, to be verified from real operation.

## 9. CCTV market check
Current Bangladesh examples:
- 4-camera Hikvision IP package around Tk 21,990
- small-office packages roughly Tk 24,500–38,500 depending brand/package

Base budget uses **Tk 35,000**.

## 10. Vaccine refrigerator market check
Current Bangladesh examples:
- 218 L 2–8°C refrigerator ~Tk 100,000
- premium 226 L model ~Tk 265,000

Base budget uses **Tk 100,000** and high case uses premium allowance.

## 11. Cost checkpoint
Base subtotal:
```
Tk 1,754,000
```

12% contingency:
```
1,754,000 × 0.12 = 210,480
```

Base total:
```
1,754,000 + 210,480
= Tk 1,964,480
≈ Tk 19.64 lakh
```
