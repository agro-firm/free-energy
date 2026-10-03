# Truck / Service Lane — Vehicle and Swept-Path Report

## Reference vehicle
Current Tata Motors Bangladesh LPT 709 reference:
- GVW: 7,500 kg
- width: 2,155 mm
- overall length: 6,225 or 6,875 mm
- height: 2,341 mm basic reference
- wheelbase: 3,400 / 3,800 mm
- minimum turning-circle diameter: 12.3 / 13.5 m

Source:
https://www.tatamotors.com.bd/bn/light-commercial-vehicles/lpt-709

## Lane-width fit
Vehicle width:
```
2.155 m
```

Lane:
```
4.267 m
```

Remaining:
```
4.267-2.155
=2.112 m
```

Centered:
```
1.056 m / 3.46 ft each side
```

## Turning
Largest reference turning circle:
```
13.5 m
=44.3 ft diameter
```

Therefore:
- no U-turn inside lane
- no three-point turn assumed within 14-ft corridor
- final entrance must be modeled with actual road width and gate flare

## Preferred movement
Reverse-in / forward-out if public-road conditions permit.

Benefits:
- forward visibility on exit
- truck can align to loading nodes
- no rearward departure through farm gate

## Spotter
Use a trained spotter for:
- all reversing
- pedestrian control
- tight loading-node positioning

## Final CAD requirement
Before construction, create a true swept-path using:
- final gate
- public-road width
- boundary walls
- actual truck wheelbase/overhang
- loading doors/canopies

The reference vehicle is not a substitute for that simulation.
