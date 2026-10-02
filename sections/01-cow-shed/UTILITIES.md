# Cow Shed — Utilities and MEP Interface Report

## 1. Utility philosophy

The shed contains only utilities necessary for animals, cleaning, manure automation, ventilation, lighting and monitoring.

**No biogas storage, treatment, or generator fuel line is permitted through the cow shed.**

Utility routes should stay visible, serviceable and protected from cows, wash water and scraper machinery.

---

## 2. Water system

### 2.1 Planning demand
Current project assumption:
```
20 cows × 80 L/cow/day = 1,600 L/day drinking water
```

The shed also uses wash water. Whole-farm cleaning is tracked in Section 13; Section 01 only needs a local header and controlled outlets.

### 2.2 Concept design flow
A planning peak was calculated as:
- 3.33 L/min peak drinking equivalent
- + one 10 L/min wash hose
- rounded concept flow ≈ **15 L/min**

### 2.3 Pipe concept
Planning only:
- main shed header: nominal 1-inch class
- trough branches: nominal 3/4-inch class
- local valve/drop: nominal 1/2-inch to 3/4-inch depending fixture

Final sizing must use:
- actual pipe internal diameter
- source pressure
- length
- static head
- simultaneous trough fill
- wash hose demand
- fittings and pressure loss

### 2.4 Route
Preferred:
- bring water from Section 13 along a dry external wall
- elevate header roughly 7–9 ft above floor where protected
- drop vertically to trough isolation valves
- avoid horizontal floor pipes crossing scraper lanes
- provide shutoff for each trough or zone

### 2.5 Trough overflow
Overflow must not cross the central feed alley.

Route overflow to:
- controlled shed drain, or
- dirty water/manure route if compatible with the waste-process design

---

## 3. Manure and dirty drainage

### 3.1 Primary manure route
```
cow platform
→ outer dirty/service strip
→ automatic scraper
→ downstream collection point
→ Section 07 waste receiving/mixing
```

### 3.2 Floor falls
Concept only:
- cow-platform cross fall: 1–1.5% toward dirty lane
- dirty-lane longitudinal fall: 0.5–1.0% toward collection

Example:
```
5.5 ft × 1.5% ≈ 0.99 in fall
48 ft × 1.0% = 5.76 in fall
```

The actual scraper supplier may require a different longitudinal slope.

### 3.3 Wash water
Wash water containing only manure-compatible cleaning should follow the dirty process route.

Do not send:
- strong disinfectant concentrate
- acid/alkaline CIP chemicals
- petroleum products
- paint/solvent
- veterinary chemical spills

into the digester without process review.

---

## 4. Stormwater

Roof rainwater must remain separate from manure drainage.

```
roof
→ gutter
→ downpipe
→ clean stormwater system
```

Do not discharge roof water into the manure sump; it would unnecessarily dilute the digester.

Gutter and downpipe sizes require local rainfall-intensity calculations.

---

## 5. Electrical system

### 5.1 Concept connected load
Current planning loads:

| Load | Concept power |
|---|---:|
| 4 circulation fans | 1.00 kW |
| 12 LED lights | 0.216 kW |
| 2 scraper drives | 2.20 kW connected |
| Optional cow brush | 0.10 kW |
| **Connected total** | **3.516 kW** |

If scraper drives do not run simultaneously, expected demand may be around 2.4–2.5 kW before future loads.

### 5.2 Distribution
Use a dedicated shed subpanel fed from the project electrical system.

Include:
- main isolator
- motor protection
- residual-current/earth-leakage protection as required
- surge protection as appropriate
- fan circuits
- lighting circuits
- scraper/control circuit
- auxiliary/socket circuit
- emergency stop circuit

### 5.3 Cable route
Preferred:
- overhead tray/conduit on structural line
- approximately Z = 9–11 ft concept zone
- drops in rigid protected conduit
- no loose cable within animal reach
- no exposed junction boxes in washdown zone

Final cable sizes, breaker ratings, short-circuit duty and voltage drop are electrical-engineer calculations.

---

## 6. Solar interface

Solar modules belong to Section 15.

Within Section 01:
- roof structure must reserve solar loading
- DC cabling should follow a controlled roof route
- roof penetrations must remain watertight
- DC equipment should not terminate in wet manure zones
- maintenance route must not require walking through cow stalls

---

## 7. Gas line rule

### Prohibited
No raw biogas, treated biogas or gas storage pipe is routed through the cow shed.

### Reason
The shed has:
- animals
- electrical loads
- moving machinery
- workers
- organic gases
- open ventilation

Biogas belongs to Sections 08–11 in the dedicated utility process zone.

---

## 8. Data and sensor system

Recommended monitoring points:

| Sensor / signal | Purpose |
|---|---|
| Shed temperature | heat-stress monitoring |
| Relative humidity | ventilation management |
| Optional ammonia sensor | air-quality trend |
| Water meter | consumption baseline |
| Water-pressure switch | detect supply failure |
| Scraper motor current | jam/overload detection |
| Scraper end-position switches | confirm travel |
| Fan run feedback | verify operation |
| Energy submeter | shed electrical consumption |
| CCTV | animal and equipment observation |

All low-voltage data cabling should be separated from power conductors per electrical practice.

---

## 9. Utility color convention

For drawings and AI engineering images:
- cyan = water
- orange/brown = manure/dirty drainage
- light blue = stormwater
- dark blue = electrical/data
- green = solar electrical route
- **do not draw gas lines inside Section 01**

---

## 10. Penetration schedule concept

Every wall/roof penetration should be documented:
- system
- diameter
- elevation
- sleeve
- seal
- weatherproofing
- fire/safety requirement if any

Avoid drilling new structural members after construction without engineer approval.
