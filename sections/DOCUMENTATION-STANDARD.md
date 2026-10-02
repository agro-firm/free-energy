# Section Documentation Standard

Every physical plant section should eventually contain the same depth of documentation as Section 01.

## Required files per section

1. `README.md`
   - section purpose
   - baseline dimensions/capacity
   - interfaces
   - document index
   - mandatory skills

2. `ARCHITECTURE.md`
   - architectural concept
   - geometry
   - area/volume
   - elevations
   - materials
   - structural concept
   - climate/ventilation/daylight
   - adjacent-section relationships

3. `BLUEPRINT.md`
   - local X/Y/Z coordinate system
   - zone dimensions
   - internal layout
   - plan and section rules
   - opening logic
   - blueprint drawing conventions

4. `DESIGN.md`
   - functional/interior design
   - user/animal/equipment workflow
   - finishes
   - safety design
   - maintainability

5. `CALCULATIONS.md`
   - math-solver format
   - area
   - volume
   - flows
   - utilities
   - sizing
   - capacity checks
   - cost checkpoints
   - FIXED/CALCULATED/ASSUMPTION/VENDOR/REGULATORY tags

6. `UTILITIES.md`
   - drainage
   - water
   - gas if applicable
   - electrical
   - data/sensors
   - utility routes
   - section interfaces
   - explicit utilities that are prohibited/not applicable

7. `PROCESS.md`
   - input/output flow
   - normal operating sequence
   - abnormal conditions
   - automation interaction
   - logs/data produced

8. `EQUIPMENT.md`
   - equipment IDs
   - quantity
   - capacity
   - dimensions when known
   - power/water/gas needs
   - vendor/engineer status
   - spare-parts notes

9. `DIAGRAMS.md`
   - plan ASCII
   - Mermaid flows
   - section diagrams
   - utility diagrams
   - context diagrams

10. `CONSTRUCTION.md`
    - construction sequence
    - materials
    - hold points
    - testing
    - commissioning
    - as-built records

11. `OPERATIONS-MAINTENANCE.md`
    - daily/weekly/monthly/annual checks
    - cleaning
    - lockout
    - maintenance
    - KPI/data

12. `BENEFITS.md`
    - operational benefit
    - hygiene/safety
    - labor
    - energy
    - revenue/value interface
    - integration benefits

13. `COST.md`
    - date/location basis
    - public source references where available
    - quantity × rate math
    - low/base/high scenarios
    - exclusions
    - operating cost allowance
    - procurement plan

14. `images/README.md`
    - image naming and governance

15. `images/IMAGE-GUIDE.md`
    - exact geometry lock
    - materials
    - all camera directions
    - interior/exterior prompts
    - adjacent-space context
    - negative constraints
    - image QA

16. `images/VIEW-MATRIX.md`
    - top
    - all elevations
    - all aerial corners
    - internal directions
    - detail views
    - utility overlays
    - context views

## Mandatory calculation format

Every important dimension/capacity calculation should show:

**Given → Unknown → Assumptions → Formula → Unit substitution → Exact result → Rounded design result → Margin → Verification**

## Mandatory image rule

No AI-generated image may redefine engineering geometry.

If a visual shows something new:
1. mark it as concept,
2. calculate it,
3. review it,
4. update the canonical files only after approval.

## Mandatory utility rule

Every section must explicitly discuss:
- water
- drainage
- electrical
- gas applicability
- data/control
- neighboring section connections

If a utility does not belong in a section, document that exclusion rather than omitting the topic.

## Mandatory cost rule

Cost files must not present one number as guaranteed.

Use:
- low
- base
- high

and clearly identify:
- public market rates
- vendor allowances
- assumptions
- exclusions
- date of estimate

## Global hierarchy

If there is a conflict:
1. current approved master plant
2. engineering-math skill
3. relevant subsystem skill
4. section blueprint/calculations
5. visualization files

Images are always last in the engineering hierarchy.
