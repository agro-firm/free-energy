# Rooftop Solar — Blueprint and Coordinate Specification

## Roof coordinates
Use cow-shed roof local:
- U=0–48 ft along ridge/eave.
- V=0–13.928 ft along each roof slope from eave to ridge.

## Plane A
12 portrait modules.
Each:
- 7.815 ft along slope.
- 3.720 ft along roof length.

Total row:
```
44.64 ft
```

End clearance:
```
(48-44.64)/2
=1.68 ft each end
```

## Plane B
Same geometry.

## Slope clearance
Total free:
```
13.928-7.815
=6.113 ft
```

Concept allocation:
- eave/gutter clearance ≈2.0 ft.
- ridge/service/vent clearance ≈4.1 ft.

Final mounting rails/roof penetrations may adjust exact panel offset.

## Strings
- String A = Plane A modules 1–12.
- String B = Plane B modules 13–24.
- MPPT1 = String A.
- MPPT2 = String B.

## Cable routing
DC home-runs:
- under/along protected roof routes.
- UV-resistant PV cable.
- metal-edge protection.
- roof penetration with weatherproof gland.
- DC isolator near inverter per final design.

## Inverter
Place off roof where possible for service and heat.
