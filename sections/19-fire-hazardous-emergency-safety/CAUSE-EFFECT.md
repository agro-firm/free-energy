# Fire / Gas Cause-and-Effect Matrix

| Event | Alarm | Gas valves | Booster | Generator | Ventilation | Upstream feed | Notes |
|---|---|---|---|---|---|---|---|
| CH₄ high Section 09/10 | YES | close as safe | STOP | inhibit | maintain safe natural/mech strategy | HOLD if needed | preserve PV relief |
| H₂S high | YES | isolate as safe | STOP | STOP/inhibit | evacuate/ventilate per plan | HOLD | SCBA/rescue only trained |
| CO high Section 11 | YES | CLOSE engine gas | STOP | STOP | purge if no fire and safe | no direct | investigate exhaust |
| Fire alarm generator | YES | CLOSE | STOP | TRIP/STOP | fire strategy TBD | no direct | avoid fan feeding fire |
| Fire alarm feed store | YES | no gas effect unless escalation | — | normal | local fire strategy | — | isolate electricity |
| Holder high-high | process alarm | normal safety logic | demand if safe | request | — | reduce/hold | flare/safe vent readiness |
| E-stop rear process | YES | close process gas as designed | STOP | STOP | safe state | HOLD | mechanical relief stays |

## Finalization
A fire/gas engineer and controls engineer must issue signed cause/effect with:
- exact detectors.
- setpoints.
- delays.
- reset rules.
- fail-safe positions.
