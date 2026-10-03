# Master Section References

## Rule
The root master files summarize the plant. They never replace detailed section files.

When a master drawing, calculation, image, BOQ or change involves a section, open the section files listed below.

| No. | Section | Folder | Primary local references |
|---:|---|---|---|
| 01 | Cow shed | `sections/01-cow-shed/` | README, ARCHITECTURE, BLUEPRINT, CALCULATIONS, UTILITIES, EQUIPMENT, IMAGE |
| 02 | Cow yard | `sections/02-cow-yard/` | README, ARCHITECTURE, BLUEPRINT, CALCULATIONS, PROCESS, IMAGE |
| 03 | Milk room + chiller | `sections/03-milk-room-chiller/` | README, ARCHITECTURE, BLUEPRINT, CALCULATIONS, UTILITIES, EQUIPMENT, IMAGE |
| 04 | Office + vet + biosecurity | `sections/04-office-vet-biosecurity/` | README, ARCHITECTURE, BLUEPRINT, CALCULATIONS, EQUIPMENT, IMAGE |
| 05 | Feed store | `sections/05-feed-store/` | README, ARCHITECTURE, BLUEPRINT, CALCULATIONS, EQUIPMENT, IMAGE |
| 06 | Feed unloading canopy | `sections/06-feed-unloading-canopy/` | README, ARCHITECTURE, BLUEPRINT, CALCULATIONS, IMAGE |
| 07 | Waste receiving + mixing | `sections/07-waste-receiving-mixing/` | README, ARCHITECTURE, BLUEPRINT, CALCULATIONS, P&ID/PROCESS, IMAGE |
| 08 | Biogas digester | `sections/08-biogas-digester/` | README, ARCHITECTURE, BLUEPRINT, CALCULATIONS, PROCESS, SAFETY, IMAGE |
| 09 | Gas storage | `sections/09-gas-storage/` | README, ARCHITECTURE, BLUEPRINT, CALCULATIONS, P&ID, SAFETY, IMAGE |
| 10 | Gas treatment | `sections/10-gas-treatment/` | README, ARCHITECTURE, BLUEPRINT, CALCULATIONS, P&ID, SAFETY, IMAGE |
| 11 | Generator + electrical | `sections/11-generator-electrical/` | README, ARCHITECTURE, BLUEPRINT, CALCULATIONS, SINGLE-LINE/P&ID, SAFETY, IMAGE |
| 12 | Fertilizer processing | `sections/12-fertilizer-processing/` | README, ARCHITECTURE, BLUEPRINT, CALCULATIONS, SOLIDS-BALANCE, P&ID, IMAGE |
| 13 | Water utility | `sections/13-water-utility/` | README, ARCHITECTURE, BLUEPRINT, WATER-BALANCE, HYDRAULICS, P&ID, IMAGE |
| 14 | Truck/service lane | `sections/14-truck-service-lane/` | README, BLUEPRINT, VEHICLE-SWEPT-PATH, PAVEMENT, DRAINAGE, IMAGE |
| 15 | Rooftop solar | `sections/15-rooftop-solar/` | README, MODULE-LAYOUT, STRING-SIZING, STRUCTURAL-ROOF, SINGLE-LINE, IMAGE |
| 16 | Master integration review | `sections/16-master-integration-review/` | INTERFACE-MATRIX, MASS-BALANCE, ENERGY-BALANCE, WATER-BALANCE, RISK-REGISTER |
| 17 | DCF-1 coordinate freeze | `sections/17-master-site-coordinate-freeze/` | COORDINATE-REGISTER, SITE-PLAN, CLASH-REPORT, IMAGE |
| 18 | Survey/Z/drainage/IFC | `sections/18-survey-z-drainage-ifc/` | SURVEY-BRIEF, LEVELS, DRAINAGE, IFC-VALIDATION |
| 19 | Fire/hazardous/emergency | `sections/19-fire-hazardous-emergency-safety/` | FIRE-RISK, HAZARDOUS-AREA, CAUSE-EFFECT, IFC-SAFETY-GATE |
| 20 | BOQ/procurement | `sections/20-master-boq-procurement/` | MASTER-BOQ.csv, DEDUP-REGISTER, PROCUREMENT-PACKAGES, COST-REPORTING |
| 21 | Construction execution | `sections/21-construction-execution-qa/` | MASTER-CONSTRUCTION-SCHEDULE, ITP-MATRIX, QA-QC, HSE, HANDOVER |
| 22 | Operations/maintenance | `sections/22-operations-maintenance-management/` | SOP-INDEX, PM-CALENDAR.csv, KPI, OPEX, BUSINESS-CONTINUITY |
| 23 | Business/financial model | `sections/23-business-financial-model/` | SCENARIO files, BREAK-EVEN, ROI-PAYBACK, FID gate |

## Image-reference rule
For every visible Section 01–15:
- read its `IMAGE.md`.
- read its `BLUEPRINT.md`.
- read its `ARCHITECTURE.md`.
- read any special layout file named in the table.

Do not infer hidden geometry from a photoreal render.

## Nonphysical section rule
Sections 16–23 may be shown only as:
- arrows.
- overlays.
- labels.
- schedules.
- dashboards.
- safety zones.
- business/financial infographics.

They are never extra buildings.
