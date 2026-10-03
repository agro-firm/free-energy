# Master Automation / I/O Matrix

## Section 07
Inputs:
- sump levels.
- mixing load cells.
- water/slurry flow.
Outputs:
- pumps.
- mixer.
- water valve.

## Section 08
Inputs:
- digester level/temp/pressure.
Outputs:
- recirculation permissive.
- feed permissive.

## Section 09
Inputs:
- holder level.
- pressure.
- gas detector.
Outputs:
- downstream demand.
- upstream inhibit.
- flare/vent request.

## Section 10
Inputs:
- H₂S.
- pressure.
- flow.
- condensate.
Outputs:
- booster.
- isolation.
- treated-gas-ready.

## Section 11
Inputs:
- gas ready.
- generator health.
- ATS source status.
- CH₄/CO.
Outputs:
- start/stop.
- gas valve.
- ATS transfer.
- load shed.

## Section 13
Inputs:
- tank levels.
- pressure.
- flow.
Outputs:
- duty/standby pumps.
- low-water shedding.

## Section 15
Inputs:
- inverter telemetry.
Outputs:
- main-bus generation only; no baseline genset parallel.

## Master SCADA tags
At minimum log:
- milk L/day.
- water m³/day.
- dung kg/day.
- slurry m³/day.
- gas m³/day.
- holder %.
- H₂S ppm.
- generator kWh.
- solar kWh.
- fertilizer kg/day.
- alarms/runtime.
