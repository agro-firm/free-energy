# Master Automation and Controls

## Architecture
Local layer:
local sensors, VFDs, relays and PLC/control panels remain with process packages.

Master layer:
central dashboard / SCADA collects whole-plant status and KPI.

## Core signals
### Section 07
- sump level.
- batch weight/flow.
- pump/mixer status.

### Section 08
- digester level.
- temperature.
- pressure.
- feed/recirculation permissive.

### Section 09
- holder level.
- gas pressure.
- gas alarm.

### Section 10
- H₂S.
- gas flow.
- inlet/outlet pressure.
- condensate.
- booster status.

### Section 11
- generator run/fault.
- ATS state.
- kW/kWh.
- CH₄/CO.
- gas ready.

### Section 13
- ground/OHT level.
- pressure.
- flow.
- pump run/fault.

### Section 15
- inverter power.
- daily/total energy.
- MPPT values.
- inverter alarm.

## Master KPI tags
- milk L/day.
- feed issue.
- water m³/day.
- dung kg/day.
- slurry m³/day.
- gas m³/day.
- generator kWh.
- solar kWh.
- fertilizer kg/day.
- PM due/overdue.
- P1/P2 alarms.

## Cause/effect principles
- gas valves fail safe.
- mechanical P/V protection remains available.
- generator stops on critical gas/CO/fire events.
- low water sheds noncritical use.
- low gas sheds generator load/returns to normal source.
- solar baseline anti-islands on grid loss.

Detailed interlocks and setpoints remain in Sections 07–15, Section 19 and approved vendor logic.
