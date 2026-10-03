---
name: visualization-images
description: Generate geometry-locked PLANT-V1.0 images using the root master image package plus every visible section's local image/blueprint/architecture files.
---

# Visualization / Image Skill

## Mandatory read order
Before a master image:
1. /IMAGE.md
2. /MASTER-COORDINATES.md
3. /MASTER-SITE-PLAN.md
4. /VIEW-MATRIX.md
5. /MASTER-SECTION-REFERENCES.md
6. every visible physical section's:
   - IMAGE.md
   - BLUEPRINT.md
   - ARCHITECTURE.md

## Geometry law
DCF-1 X/Y is fixed.

Do not:
- move buildings.
- resize sections.
- swap lane side.
- add physical Sections 16–23.
- change solar count.
- invent survey Z.

## Physical sections
Only 01–15 are physical.

16–23 are overlays/data/control only.

## Master image QA
Use the checklist in /IMAGE.md.

If a generated image drifts:
regenerate it.

Do not reinterpret the drift as a design revision.

## View authority
Use /VIEW-MATRIX.md for master camera/view selection.

Use local section image files for close-ups.

## Flow colors
- milk blue.
- feed amber.
- manure brown.
- raw gas dark green.
- treated gas light green.
- digestate yellow/gold.
- water cyan.
- electricity dark blue.
- traffic grey.
- safety red.
- solar gold.
