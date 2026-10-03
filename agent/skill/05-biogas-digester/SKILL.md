---
name: biogas-digester
description: Size, place and operate the anaerobic digester for the 20-cow waste stream.
---

# Biogas Digester Skill

## Canonical planning baseline
- Digester type: **semi-buried cylindrical RCC low-pressure anaerobic digester**.
- Compound: **16 × 20 ft**.
- Total internal vessel volume: **25 m³**.
- Selected target working liquid volume: **20 m³**.
- Minimum hydraulic volume at 30-day HRT: **16.2 m³**.
- Target HRT at 20 m³ working volume: **~37 days**.
- Process headspace/freeboard: **~5 m³**.
- Planning internal diameter: **2.8 m**.
- Planning total internal height: **~4.06 m**.
- Separate raw-gas storage remains downstream in Section 09.

## Hydraulic sizing
```
minimum_working_volume = 0.54 m³/day × 30 days
= 16.2 m³
```

Selected:
```
20 / 0.54
= 37.04 days HRT
```

The 25 m³ total concept therefore contains:
- ~20 m³ target liquid working volume
- ~5 m³ gas/freeboard volume

## Process sequence
Section 07 metered slurry → submerged digester inlet → anaerobic digestion → gas headspace → condensate protection → Section 09 raw-gas storage.

Digestate displacement/overflow → Section 12 fertilizer/digestate handling.

## Planning biological range
- Feed slurry: ~0.54 m³/day.
- Feed total-solids estimate: ~9.5% using the current 19% fresh-dung TS assumption and 1:1 dilution.
- Planning process temperature: ambient/mesophilic operation, roughly 25–35°C desirable.
- Planning pH operating band: roughly 6.8–7.5.
- Final loading, startup and monitoring targets require biogas-process specialist/vendor review.

## Must define before construction/procurement
- Final RCC wall/base/roof thickness and reinforcement.
- Soil bearing, uplift and groundwater design.
- Final inlet/outlet elevations.
- Pressure/vacuum relief settings and sizing.
- Gas-tight roof/manway detail.
- Recirculation/mixing method.
- Hazardous-area classification.
- Gas detector locations.
- Digestate overflow chamber and downstream hydraulics.

## Rule
Do not treat the conceptual geometry as a pressure-vessel design. Structural, gas-safety, pressure/vacuum, hazardous-area and foundation details require qualified engineers.
