# Waste Receiving + Mixing — P&ID Concept

## Equipment tags
- SC-101 — coarse screen
- GP-101 — grit pocket
- RS-101 — receiving sump
- P-101 — receiving transfer pump
- MT-101 — mixing tank
- M-101 — mixer
- P-102 — digester feed pump
- ES-101 — emergency sump
- PLC-101 — local process controller

## Instruments
- LSL-101 — receiving sump low
- LSH-101 — receiving sump high
- LSHH-101 — receiving sump high-high
- WIT-101 — mixing-tank weight indication/transmitter
- FIT-201 — dilution-water flow/total
- FIT-301 — slurry flow/total to digester
- LSH-401 — emergency sump high
- LSHH-401 — emergency sump high-high
- DI-501 — Section 08 digester-ready/high inhibit
- GD-101 — optional H₂S/CH₄ detector

## Valves
- HV-201 — manual water isolation
- XV-201 — automatic water valve
- HV-301 — feed-line isolation
- NRV-301 — feed-line non-return
- HV-401 — emergency/manual isolation
- cleanout valves at low points/vendor positions

## P&ID flow
```text
Cow Shed
   |
   v
SC-101 --> GP-101 --> RS-101
                       |                        |  --> ES-101 emergency containment
                       v
                    P-101
                       |
                       v
                  MT-101 <--- HV-201 --- FIT-201 --- XV-201 --- Water
                   |   |
                WIT   M-101
                   |
                   v
                 P-102
                   |
                HV-301
                   |
                NRV-301
                   |
                FIT-301
                   |
                   v
              Section 08 Digester
```

## Signal philosophy
PLC reads level/load/flow signals and commands P-101, M-101, XV-201 and P-102. Digester-ready is a hard process permissive. Final SIL/safety classification is not defined in this concept.
