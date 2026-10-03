# Water Utility — Automation

## Modes
OFF / MANUAL / AUTO / MAINTENANCE

## Duty alternation
Each fill/pressure cycle alternates P-701A and P-701B.

## Start
Pump starts on:
- pressure low
- OHT low request
- approved process demand

## Stop
- pressure high
- OHT high
- GT low-low
- fault

## Leak detection
If flow persists above configurable minimum during normally idle period:
- alarm
- log branch investigation

## Priority shedding
At GT low:
1. disable wash hoses
2. disable noncritical process cleaning
3. keep drinking/milk hygiene/digester minimum
