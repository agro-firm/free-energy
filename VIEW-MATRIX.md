# MASTER VIEW MATRIX

## Whole-site views
| ID | View | Visible physical sections | Mandatory local references |
|---|---|---|---|
| M00 | True orthographic top | 01–15 | all section IMAGE/BLUEPRINT summaries + Section 17 |
| M01 | SW aerial | 01–15 | all visible section IMAGE files |
| M02 | SE aerial | 01–15 | all visible section IMAGE files |
| M03 | NW aerial | 01–15 | all visible section IMAGE files |
| M04 | NE aerial | 01–15 | all visible section IMAGE files |
| M05 | Front/public view | 04,13,05,06,14 + background 01/03 | 04/13/05/06/14 |
| M06 | East service-lane view | 06,03,11,12,14 | 06/03/11/12/14 |
| M07 | West livestock view | 01,02 | 01/02 |
| M08 | Rear energy/fertilizer view | 08,09,10,11,12,14 | 08–12/14 |

## Functional close master views
| ID | View | Sections |
|---|---|---|
| M09 | Dairy core | 01,03,13 |
| M10 | Feed logistics | 05,06,14,01 |
| M11 | Manure-to-digester | 01,07,08 |
| M12 | Gas-to-generator | 08,09,10,11 |
| M13 | Digestate/fertilizer | 08,12,14 |
| M14 | Water network | 13 + users |
| M15 | Solar roof | 01,15 |
| M16 | Milk pickup | 03,14 |
| M17 | Feed unloading | 05,06,14 |
| M18 | Generator service | 10,11,14 |
| M19 | Fertilizer dispatch | 12,14 |

## Engineering overlays
| ID | Overlay |
|---|---|
| M20 | section numbers + DCF coordinates |
| M21 | clean/dirty zones |
| M22 | milk/feed/manure/gas/digestate process flows |
| M23 | clean-water distribution |
| M24 | electrical/renewable topology |
| M25 | clean storm vs dirty drainage |
| M26 | fire/hazardous-area pending zones |
| M27 | automation/SCADA architecture |
| M28 | construction phases |
| M29 | operations/KPI dashboard |
| M30 | business/CAPEX/EBITDA dashboard |

## Overlay rule
M20–M30 may use Sections 16–23 information, but those section numbers are labels/data only, not buildings.

## Detail rule
When a view includes a physical section prominently, its local `IMAGE.md`, `BLUEPRINT.md` and `ARCHITECTURE.md` must be consulted before generation.
