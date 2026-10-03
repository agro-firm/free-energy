---
name: solar
description: Design and verify the 15 kWp cow-shed rooftop solar system.
---

# Solar Skill

## Canonical baseline
- Target/selected DC size: **15.0 kWp**.
- Modules: **24 ×625 W**.
- Module dimensions: **2382 ×1134 mm**.
- Roof: cow-shed gable, 26 ×48 ft, ~21.04° pitch.
- Layout: **12 modules on each roof plane, portrait, one row per slope**.
- Strings: **2 ×12 modules**.
- Inverter: **15 kW, three-phase, 2-MPPT approved grid-tied class**.
- Each roof plane goes to its own MPPT.
- Planning yield: **3.89 kWh/kWp/day**.

## Electrical baseline
Using 625 W module planning data:
- Vmp ≈41.4 V.
- Imp ≈15.11 A.
- Voc ≈48.6 V.
- Isc ≈16.14 A.

Per 12-module string:
- Vmp ≈496.8 V.
- Voc ≈583.2 V.
- cold Voc at 0°C planning ≈619.7 V.
- current remains module current.

## Layout rules
- no module beyond roof edge.
- keep ridge ventilation and access.
- keep eave/gutter access.
- reserve end clearances.
- do not cover roof service penetrations.
- use two MPPTs for two roof azimuths.

## Structure
Module dead load alone ≈6.34 kg/m² averaged over full sloped roof.
Mounting/cables add additional load.
Wind uplift governs many connections and must be structurally engineered.

## Integration
- normal solar: grid/main-bus operation.
- generator: Essential Load Board through ATS.
- no uncontrolled AC coupling between grid-tied inverter and generator island.

## Rule
Final string design, inverter model, roof attachment, cable sizes, protection, net-metering and utility interconnection must be verified from exact equipment datasheets and current SREDA/utility requirements.
