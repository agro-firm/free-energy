# Biogas Digester — P&ID Concept

## Tags
- DG-201 digester
- P-201 recirculation pump
- TI-201 slurry temperature
- LI/LIT-201 liquid level
- PI/PIT-201 gas pressure
- PVSV-201 pressure/vacuum safety valve
- CT-201 condensate trap
- OV-201 digestate overflow
- CH-201 digestate outlet chamber
- GD-201 gas detector
- MH-201 manway

## Concept
```text
Section 07 Slurry
      |
    HV-201
      |
    IN-201
      |
      v
+-----------------------+
|       DG-201          |
|   gas headspace       |---- GO-201 ---- CT-201 ----> Section 09
|      PIT-201          |         |
|      PVSV-201 --------|---------+--> safe relief path
|-----------------------|
|   20 m³ liquid        |
| TI-201 / LIT-201      |
|                       |---- OV-201 ---> CH-201 ---> Section 12
+-----------------------+
       |         ^
       |         |
       +--> P-201+     recirculation loop
```

## Important rule
The pressure/vacuum safety path must not depend on PLC software and must remain available if normal gas transfer is isolated.

## Signals
Section 07 receives:
- digester ready
- liquid high/high-high
- gas pressure high/high-high
- maintenance lockout

Section 09 receives:
- raw gas from GO-201
- gas pressure status as required

Section 12 receives:
- digestate overflow
- outlet-blockage status if instrumented
