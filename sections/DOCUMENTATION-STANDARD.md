# Section Documentation Standard

Every physical plant section should eventually contain the same depth of documentation as Section 01.

## Required files per section

1. `README.md` — purpose, baseline, interfaces, file index and mandatory skills.
2. `ARCHITECTURE.md` — architecture, geometry, materials, structure, climate and adjacency.
3. `BLUEPRINT.md` — local X/Y/Z coordinates, dimensions, zones, openings and drawing rules.
4. `DESIGN.md` — functional/interior design, workflow, finishes, safety and maintainability.
5. `CALCULATIONS.md` — math-solver calculations, capacities, sizing and value tags.
6. `UTILITIES.md` — drainage, water, gas applicability, electrical, data/control and interfaces.
7. `PROCESS.md` — inputs/outputs, normal sequence, abnormal conditions and data logging.
8. `EQUIPMENT.md` — IDs, quantity, dimensions/capacity, utilities and vendor/engineer status.
9. `DIAGRAMS.md` — ASCII, Mermaid, plan, section, utilities and context diagrams.
10. `CONSTRUCTION.md` — sequence, materials, hold points, testing and commissioning.
11. `OPERATIONS-MAINTENANCE.md` — daily/weekly/monthly/annual operation and maintenance.
12. `BENEFITS.md` — operational, hygiene, labor, energy, safety and value benefits.
13. `COST.md` — date/location basis, quantity×rate math, low/base/high, exclusions and procurement.
14. `IMAGE.md` — **canonical image-generation source of truth** containing:
    - fixed geometry
    - image calculations/proportions
    - coordinate system
    - prompt templates
    - all image categories
    - camera logic
    - material/style rules
    - utility-overlay rules
    - adjacent-section context
    - negative prompts
    - image QA
15. `images/README.md` — image naming and governance.
16. `images/IMAGE-GUIDE.md` — detailed image prompts and rendering specifications.
17. `images/VIEW-MATRIX.md` — all camera directions, interiors, details, overlays and context views.

## Mandatory calculation format
**Given → Unknown → Assumptions → Formula → Unit substitution → Exact result → Rounded design result → Margin → Verification**

## Mandatory image rule
No AI-generated image may redefine engineering geometry. If a visual proposes something new: mark it concept → calculate → review → approve → update canonical files.

## Mandatory utility rule
Every section must explicitly discuss water, drainage, electrical, gas applicability, data/control and neighboring connections. If a utility does not belong there, document its exclusion.

## Mandatory cost rule
Use low/base/high scenarios and clearly identify public rates, vendor allowances, assumptions, exclusions and estimate date.

## Global hierarchy
1. current approved master plant
2. engineering-math skill
3. relevant subsystem skill
4. section blueprint/calculations
5. section IMAGE.md
6. visualization files
7. generated image

Images are always last in the engineering hierarchy.
