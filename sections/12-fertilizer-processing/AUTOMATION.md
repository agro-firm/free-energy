# Fertilizer Processing — Automation and Controls

## Modes
- OFF
- AUTO DAILY RUN
- MANUAL
- MAINTENANCE

## Auto start
Require:
- BT-601 minimum level
- LT-601 free capacity
- SP-601 ready
- no E-stop
- no motor fault

## Sequence
1. start screw press
2. verify running
3. start P-601
4. process until BT low or target run volume/time
5. stop P-601
6. allow screw press clear-out
7. stop SP-601
8. log runtime/batch

## Trips
- screw-press overload
- no discharge
- LT high-high
- P-601 fault
- E-stop

## Drying fans
Timer/manual based on weather/humidity.
Not tied to separator safety logic.

## Bagging
Mostly manual.
Optional:
- bag count
- scale serial logging
- moisture-entry field

## Data
- digestate processed kg/m³
- press runtime
- estimated cake kg
- liquid tank level
- bags produced
- bag weights
- moisture
- lab batch
