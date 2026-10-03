# Gas Storage — P&ID Concept

## Tags
- GH-301 gas holder
- CT-301 condensate pot
- LIT-301 holder level/position
- PIT-301 holder pressure
- PVSV-301 pressure/vacuum safety
- XV-301 inlet isolation
- XV-302 outlet isolation
- GD-301 CH₄/H₂S detector
- FL-301 safe vent/flare interface
- CP-301 controls

## Concept
```text
Section 08
   |
   v
Primary Condensate
   |
 XV-301
   |
 CT-301
   |
   +------ PIT-301
   |
   v
+-------------------+
|      GH-301       |
|   8 m³ membrane   |<---- LIT-301
+-------------------+
   |
 XV-302
   |
   +---------------------------> Section 10 Treatment
   |
   +---- PVSV-301 ----> FL-301 safe vent/flare path

GD-301 monitors storage zone atmosphere.
```

## Safety rule
PVSV-301/FL-301 protection must remain available regardless of CP-301/PLC state.

## Interfaces
Section 08 receives:
- holder high/high-high inhibit request

Section 10 receives:
- gas available
- holder pressure/level status

Section 11 receives indirectly:
- generator demand enable from Section 09/10 control sequence
