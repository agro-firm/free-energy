# Generator + Electrical — Power Architecture

## Mode A — normal grid/solar
- main farm bus energized
- solar contributes according to Section 15
- Essential Load Board receives normal source through ATS
- generator stopped
- gas accumulates in Section 09

## Mode B — gas-use cycle with grid available
When holder ≥75% and gas treatment ready:
1. start generator unloaded
2. stabilize voltage/frequency
3. ATS disconnects normal source
4. ATS connects generator to Essential Load Board
5. staged essential loads run
6. nonessential loads remain on main grid/solar bus
7. stop cycle around holder low threshold
8. ATS returns essential board to normal source

This uses biogas without grid export or synchronization.

## Mode C — grid failure
If holder level and gas quality permit:
- generator may start at lower emergency threshold (~30% planning)
- Essential Load Board is energized
- noncritical farm bus remains off unless separate backup exists

## Mode D — no gas
Essential Load Board relies on:
- normal grid
- future approved solar/battery backup
- not the empty biogas generator

## Mode E — high gas, generator unavailable
Section 09/10 handles:
- upstream feed reduction
- safe flare/vent logic
- alarms

Do not force a faulted generator to start merely to consume gas.

## Solar/generator rule
Baseline:
**no paralleling**.

Future parallel operation would require:
- inverter supports genset
- anti-islanding/synchronization
- reverse-power protection
- power-factor/reactive control
- minimum genset loading
- manufacturer approval
- formal redesign

## Metering
Track:
- solar kWh
- grid import/export if applicable
- generator kWh
- generator gas m³
- essential-bus kWh
