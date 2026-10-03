# Generator + Electrical — Operating Process

## Normal gas-use start
1. holder ≥75%
2. Section 10 treated-gas-ready
3. ATS available
4. critical alarms clear
5. ventilation starts
6. confirm airflow
7. open gas permissive/start cranking
8. engine starts
9. verify oil pressure/temperature
10. stabilize 230 V / 50 Hz
11. close generator breaker
12. ATS transfers essential bus
13. stage loads
14. run around 4 kW target

## Stop at low gas
1. holder approaches 20%
2. shed Tier 2 loads
3. ATS returns essential bus to normal source if available
4. generator unloads
5. cool-down per vendor
6. close gas solenoid
7. stop engine
8. ventilation post-run
9. log cycle

## Grid failure emergency
If holder ≥~30% and gas ready:
- start generator
- energize Tier 1 first
- add Tier 2 only with capacity margin
- stop at 20% holder threshold

## Overload
- shed Tier 2
- inhibit new motors
- if overload remains, transfer/remove load and stop safely

## Gas quality fault
- close gas valve
- trip/stop generator
- return ATS to normal if available
- Section 10 alarm

## Ventilation failure
- alarm
- if adequate cooling cannot be guaranteed, unload and stop generator

## CO/CH₄ alarm
- close gas
- stop generator
- keep safe ventilation running if electrical classification/control permits
- evacuate/investigate

## Engine fault
Trip on vendor protections:
- low oil pressure
- overtemperature
- overspeed
- over/under voltage
- over/under frequency
- overcurrent

## Black start
Generator can start from 12 V starter battery without AC supply, provided gas treatment/control systems needed for safe start are on backup power.
