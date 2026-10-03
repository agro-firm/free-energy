# Master Change Control

## Change levels
### Level 0 — no design change
Editorial clarification only.

### Level 1 — local section change
Does not alter:
- DCF rectangle.
- plant capacity.
- adjacent interface.
- master flow.

Update local section and check root master impact.

### Level 2 — master interface/capacity change
Changes:
- utilities.
- equipment capacity.
- process flow.
- controls.
- access.
- adjacent section.

Update root master + all affected sections.

### Level 3 — DCF/master-layout change
Moves/resizes a physical section or service lane.

Mandatory:
- Section 17 coordinate/clash revision.
- master site plan.
- interfaces.
- safety.
- drainage.
- images.
- BOQ.
- construction.
- business.

## Change request must state
1. requested change.
2. reason.
3. current condition.
4. sections affected.
5. geometry.
6. process.
7. water.
8. power.
9. drainage.
10. safety/regulatory.
11. controls.
12. CAPEX/OPEX.
13. schedule.
14. image/document impact.

## Vendor substitution
No silent substitution.

Review:
- dimensions.
- performance.
- utilities.
- materials.
- certifications.
- controls.
- maintenance/spares.
- cost.
- lead time.

## Canonical versioning
Current:
```
PLANT-V1.0 / DCF-1
```

Major layout/capacity reconfiguration should create a new controlled plant version.
