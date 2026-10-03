# Generator + Electrical — Automation and ATS Logic

## Modes
- OFF
- AUTO GAS-CYCLE
- AUTO EMERGENCY
- MANUAL TEST
- MAINTENANCE

## Gas-cycle start permissives
- Section 09 holder ≥75%
- Section 10 treated gas ready
- no gas/CO alarm
- E-stop reset
- ventilation available
- generator controller healthy
- ATS normal source present/transfer available
- essential bus within load plan

## Emergency start
Grid/normal source lost:
- if holder ≥30% planning and treated gas ready, generator may start
- Tier 1 loads only initially

## Start sequence
1. start ventilation
2. verify airflow
3. energize controller/battery checks
4. open gas start sequence
5. crank
6. verify engine speed/oil
7. verify voltage/frequency
8. close generator breaker
9. ATS break-before-make transfer
10. energize Tier 1
11. delay/stage Tier 2

## Load management
If kW >4.3 kW or current approaches protective limit:
- drop Tier 2
- block motor starts

If overload persists:
- trip/stop according to protection coordination

## Stop
- shed Tier 2
- ATS transfer back normal if available
- unload
- cool down
- close gas
- stop
- ventilation post-run

## Trips
Immediate/controlled trip as appropriate:
- CH₄ alarm
- CO alarm
- engine overspeed
- oil pressure
- overtemperature
- severe over/under voltage
- severe over/under frequency
- breaker fault
- Section 10 H₂S/gas-quality fault
- ventilation failure with high room temperature
- E-stop

## Solar rule
No automatic genset/solar paralleling in baseline.

## Logs
- start/stop reason
- run time
- gas m³
- kWh
- average kW
- max current
- ATS transfers
- load-shed events
- alarms
- battery voltage
