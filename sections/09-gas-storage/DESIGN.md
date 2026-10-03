# Gas Storage — Functional Design

## 1. Storage role
The gas holder buffers production/consumption mismatch.

Digester:
```
8.10–9.18 m³/day
```

Generator/treatment demand is intermittent, so storage prevents:
- constant engine cycling
- unnecessary venting
- unstable downstream pressure/flow

## 2. Storage technology
Baseline:
**custom double-layer reinforced flexible raw-biogas bag in protective ventilated cage**.

Required membrane properties:
- gas-tight
- H₂S resistant
- condensate/moisture resistant
- UV resistant
- flame-retardant specification
- welded seams
- documented gas permeability
- documented service temperature

Vendor may propose PVC/PVDF/TPU coated reinforced fabric.

## 3. Double-membrane alternative
A vendor-engineered free-standing double-membrane holder is acceptable if:
- nominal usable volume ≥8 m³
- it physically fits 10×12 ft
- pressure/air-blower package fits
- hazardous-area/safety design is acceptable
- cost is justified

Because many standard double-membrane products start at much larger capacities, the small flexible holder remains the baseline.

## 4. Control by volume
Recommended conceptual thresholds:
- 20% low cutout = 1.6 m³
- 30% low warning = 2.4 m³
- 75% downstream generation enable = 6.0 m³
- 90% high warning = 7.2 m³
- 95% high-high process action = 7.6 m³

These are control concepts, not membrane structural limits.

## 5. Pressure
Holder pressure is kept very low.

Public double-membrane sources commonly publish working pressure on the order of a few mbar, but the project **does not adopt those public values as setpoints**.

Vendor/engineer defines:
- normal pressure
- low pressure/vacuum alarm
- high pressure alarm
- relief setpoint
- allowable vacuum

## 6. Filling
Raw gas enters from Section 08 after condensate protection.
As membrane expands:
- volume rises
- level sensor tracks fill
- pressure remains within holder operating band

## 7. Withdrawal
Section 10 draws raw gas for:
- H₂S treatment
- fine moisture removal
- metering
- pressure boost/regulation
- generator

If holder falls to low cutout, downstream generator demand stops.

## 8. Condensate
Raw biogas remains wet.
Provide:
- inlet low-point condensate collection
- sloped gas piping
- accessible closed drain
- no water pooling in membrane inlet/outlet

## 9. Emergency high volume
At high/high-high holder level:
1. stop/limit Section 08 feeding if necessary
2. enable downstream demand if available
3. route excess gas through engineered safe flare/vent logic
4. never depend on bag rupture as pressure protection

## 10. Low volume
At low:
- stop generator withdrawal
- prevent bag collapse/vacuum
- maintain gas-treatment standby
- digester may continue producing

## 11. Membrane handling
Never:
- walk on inflated bag
- place tools on bag
- use rope/chains directly on membrane
- patch without approved material/procedure
- pressure test above vendor limit
