# Gas Treatment — Automation and Controls

## Modes
- OFF
- STANDBY
- READY
- RUN
- MEDIA SERVICE
- EMERGENCY

## Ready conditions
- Section 09 holder above low threshold
- no gas alarm
- inlet/outlet pressure valid
- condensate not high
- at least one H₂S path online
- outlet H₂S below limit
- filter ΔP acceptable
- Section 11 ready if run requested

## Start sequence
1. open approved gas path
2. verify pressures
3. confirm H₂S outlet acceptable
4. start booster if required
5. control outlet pressure
6. verify gas flow
7. issue treated-gas-ready to Section 11

## H₂S alarms
Planning:
- warning before generator maximum
- trip at/above generator H₂S limit

Exact ppm setpoints use Section 11 vendor requirement.

## Media breakthrough
Trend AIT-401 and manual samples.
If lead breakthrough detected:
- switch lead/lag order according to procedure
- service exhausted vessel
- no bypass

## Pressure
Low suction:
- reduce/stop booster
- protect Section 09 from vacuum

High discharge:
- stop booster
- close generator feed if required
- alarm

## Flow
Generator command with no gas flow:
- stop generator start sequence
- alarm valve/booster blockage

Unexpected flow when stopped:
- isolate
- alarm valve leakage

## Condensate
KO/MS high:
- stop if liquid carryover risk
- drain safely

## Gas detector
High:
- stop booster
- close auto isolation where safe
- inhibit generator
- emergency alarm

## Data logging
- H₂S ppm
- flow m³/h and daily m³
- inlet/outlet pressure
- booster runtime
- media hours/gas volume
- ΔP
- condensate drains
- alarms
