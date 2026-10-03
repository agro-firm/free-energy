# Master Site Coordinates and Area Balance

## Global coordinate framework
Use after survey:
- origin: southwest/front property corner.
- X: 0–65 ft across plot.
- Y: 0–95 ft front to rear.
- Z: surveyed site datum.

## Service lane
Canonical:
- 14 ft wide.
- 95 ft long.
- runs along one full site side.
- exact east/west side is not yet frozen globally in the repo.

## Ground-area accounting
Physical footprints excluding rooftop solar:
- Sections 01–13 + Section 14 lane ≈5,330 ft².
- Plot =6,175 ft².
- Residual =845 ft².

```
5330/6175=86.3% allocated
845/6175=13.7% residual
```

Residual area is not “unused.” It must absorb:
- maintenance gaps.
- drainage.
- fire/safety separation.
- door swing.
- pipe/cable corridors.
- ventilation buffers.
- truck transition space.

## Integration hold point
Do not invent final global rectangles by copying local section coordinates.

Required before IFC:
1. boundary survey.
2. road/gate survey.
3. spot elevations.
4. groundwater/flood information.
5. exact section rectangles placed at scale.
6. clash check.
7. swept-path check.
8. utility crossing check.
9. drainage outfall.
10. safety-separation review.

## Global placement priorities
- Office/biosecurity near public entry.
- Milk room on clean service-lane node.
- Feed canopy/store on feed node.
- Cow shed central to milk/feed/waste.
- Waste receiving directly downstream of cow shed.
- Digester immediately after waste receiving.
- Gas holder → treatment → generator in process order.
- Fertilizer downstream of digestate and adjacent service lane.
- Water utility accessible but isolated from dirty drains.
