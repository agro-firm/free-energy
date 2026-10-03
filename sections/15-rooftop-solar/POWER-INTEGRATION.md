# Rooftop Solar — Power Integration

## Baseline
Grid/main farm bus:
```
PV inverter → Solar ACDB → Main MDB
```

Biogas generator:
```
GEN → ATS → Essential Load Board
```

## No uncontrolled AC coupling
When ATS puts Essential Load Board on generator:
- grid-tied solar is not allowed to energize that island.
- generator sees no reverse power from PV.

## Normal daytime
Solar supplies farm loads first according to electrical topology.
Surplus may export under approved net metering.

## Grid outage
Conventional on-grid inverter anti-islands and shuts down.
The biogas generator can independently feed Essential Load Board.

## Future hybrid option
A hybrid/grid-forming design could coordinate:
- solar.
- battery.
- generator.
- grid.

That is not included in this baseline and requires formal redesign.

## Three-phase assumption
15 kW baseline inverter is three-phase.
If actual utility service is not three-phase:
- confirm upgrade.
- or select utility-approved alternative architecture.
