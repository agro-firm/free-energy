# Generator + Electrical — Treated Gas Interface

## Source
Section 10 supplies:
- H₂S within generator limit
- no free liquid
- filtered gas
- measured gas flow
- stable low-pressure gas
- treated-gas-ready signal

## Local train
At Section 11:
1. manual room isolation valve
2. normally-closed automatic gas shutoff
3. local pressure point/switch
4. flexible gas connector
5. engine gas mixer/regulator/carburetion system
6. backfire/flame-arrestor device only if specified by genset vendor

## Flow
Normal at 4 kW:
```
≈2.23 m³/h
```

Full 5 kW:
```
≈2.79 m³/h
```

Section 10 design:
```
3 m³/h
```

## Gas permissives
Gas valve opens only when:
- generator cranking/start sequence active
- Section 10 treated gas ready
- room CH₄ alarm clear
- E-stop reset
- engine controller healthy

Gas valve closes on:
- engine stop
- overspeed
- oil-pressure fault
- overtemperature
- gas alarm
- E-stop
- fire input
- Section 10 quality fault

## Pressure
No fixed project mbar value is stated.
Section 10 booster/regulator and genset vendor define:
- minimum inlet
- nominal inlet
- maximum inlet

## Piping
Trunk may remain DN40 from Section 10.
Local branch can reduce to vendor engine inlet size.
Use gas-rated hose/flex only at final engine vibration connection.

## No storage
No gas cylinder, gas bag or buffer tank inside generator room.
