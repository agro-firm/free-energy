# Benchmark and Datum

## DCF plan datum
X/Y:
- Section 17 remains authoritative.

## Temporary vertical datum
For drawing coordination only:
```
D0=(51,0)
DRD(D0)=100.000 m
```

This is not a national or surveyed RL.

## Conversion after survey
Let:
- RL_D0 = surveyed RL at D0.
- RL_P = surveyed RL at any point P.

Then:
```
Z_project(P)
=100.000 + RL_P - RL_D0
```

## Example
If:
```
RL_D0=4.250 m
RL_P=4.380 m
```

Then:
```
Z_project(P)=100.130 m
```

The example is arithmetic only and not site data.

## Benchmarks
Final IFC drawings show:
- TBM-01 RL.
- TBM-02 RL.
- project datum relationship.
- datum authority/source.

## Rule
No contractor may establish site level from an arbitrary road edge, wall top or temporary peg.
