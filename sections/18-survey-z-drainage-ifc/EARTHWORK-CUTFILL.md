# Earthwork / Cut-Fill

## Survey surface
Create existing-ground TIN/grid from field data.

## Proposed surface
Build final grading surface from:
- road tie-in.
- lane crossfall.
- FFL platforms.
- clean drainage.
- dirty process containment.
- outfall.

## Grid method
For each grid cell:
```
V = cell_area × average(proposed_level - existing_level)
```

Separate:
- fill.
- cut.
- topsoil strip.
- unsuitable material.
- imported granular fill.

## Factors
Engineer/contractor applies:
- compaction.
- shrink/swell.
- unsuitable replacement.
- settlement allowance.

## Goal
Balance cut/fill where practical, but never lower critical FFL merely to save fill.

## Output
- cut volume.
- fill volume.
- net import/export.
- topsoil quantity.
- subgrade improvement.
- disposal/source plan.
