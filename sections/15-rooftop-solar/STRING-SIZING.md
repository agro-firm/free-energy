# Rooftop Solar — String and Inverter Sizing

## Array
2 strings ×12 modules.

## Per string
```
P=12×625
=7.5 kWp
```

```
Vmp≈496.8 V
Voc≈583.2 V
Imp≈15.11 A
Isc≈16.14 A
```

## Inverter example
SREDA-approved Sungrow SG15RT-P2:
- 15 kW AC.
- 1100 V max DC.
- 160–1000 V MPPT range.
- 2 independent MPPTs.
- 32 A per MPPT max input-current class.
- 40 A per MPPT short-circuit-current class.

Each 12-module string fits comfortably in voltage/current limits.

## MPPT mapping
- Plane A → MPPT1.
- Plane B → MPPT2.

## Bifacial current
Do not assume high rear gain on metal roof.
If vendor predicts rear gain causing current beyond selected inverter/string input rating, use a higher-current approved inverter or adjust module selection.

## Cold voltage
0°C planning:
```
~619.7 V/string
```

Still well below 1100 V.

## Hot operation
String Vmp remains far above inverter start/MPPT minimum; final hot-cell voltage is verified in vendor software.
