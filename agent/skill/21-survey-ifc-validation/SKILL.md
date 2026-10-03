---
name: survey-ifc-validation
description: Convert DCF-1 X/Y design coordinates into surveyed Z levels, coordinated drainage/earthwork and an IFC-ready site package.
---

# Survey + IFC Validation Skill

## Scope
- DCF-1 X/Y stays fixed unless formal change control is approved.
- Field survey supplies actual RL/Z values.
- Section 18 controls project datum, spot levels, finished-floor rules, drainage hydraulics, cut/fill, outfall selection, setting-out QA and IFC release.

## Critical rule
Never label a provisional/project datum as a surveyed elevation.

## Project datum
Use a temporary design datum only for coordination:
- D0=(51,0) at building-side edge of service lane.
- DRD(D0)=100.000 m.
- After survey:
  Z_project(point)=100.000 + RL_field(point) - RL_field(D0).

## Final IFC prerequisites
1. Licensed boundary/topographic survey.
2. Two stable benchmarks.
3. Public-road/gate cross-section.
4. Outfall invert/headwater.
5. Flood/high-water evidence.
6. Groundwater/geotechnical information.
7. Drainage calculations using current rainfall/IDF criteria.
8. Finished floor/freeboard schedule.
9. Earthwork/cut-fill balance.
10. Fire/gas/electrical interface review.
11. Vendor footprint/level checks.
12. Independent setting-out QA.

## Reference methods
For small drainage catchments, use current accepted hydrologic methods; LGED drainage references use Modified Rational flow estimation and Manning hydraulic checks. Final design intensity/return period must be selected by the civil engineer from current local criteria/data.
