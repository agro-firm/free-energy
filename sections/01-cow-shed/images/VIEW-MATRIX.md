# Cow Shed — Image View Matrix

## 1. Required master views

| ID | View | Camera concept | Main purpose |
|---|---|---|---|
| V01 | Top orthographic | (24,13,70) | blueprint/layout |
| V02 | South elevation | (24,-45,8) | long-side architecture |
| V03 | North elevation | (24,71,8) | opposite long side |
| V04 | West elevation | (-45,13,8) | gable/feed access |
| V05 | East elevation | (93,13,8) | gable/service access |
| V06 | SW aerial | (-25,-25,32) | 3D overview |
| V07 | SE aerial | (73,-25,32) | 3D overview |
| V08 | NW aerial | (-25,51,32) | 3D overview |
| V09 | NE aerial | (73,51,32) | 3D overview |

## 2. Required interior views

| ID | View | Camera | Must show |
|---|---|---|---|
| I01 | Feed alley W→E | (5,13,5.5) | both rows, mangers, roof |
| I02 | Feed alley E→W | (43,13,5.5) | reverse interior |
| I03 | South row | (24,9.5,5.5) | cow platform/rail |
| I04 | North row | (24,16.5,5.5) | opposite row |
| I05 | South scraper lane | (5,1.5,3) | scraper and dirty lane |
| I06 | North scraper lane | (5,24.5,3) | scraper and dirty lane |
| I07 | End cross zone west | (2,13,5) | end circulation |
| I08 | End cross zone east | (46,13,5) | end circulation |

## 3. Detail views

| ID | Detail |
|---|---|
| D01 | manger edge and stall rail |
| D02 | water trough and valve |
| D03 | scraper blade/drive concept |
| D04 | floor slope/gutter transition |
| D05 | fan mounting |
| D06 | LED/electrical tray |
| D07 | roof gutter/downpipe |
| D08 | ridge ventilation |
| D09 | CCTV/sensor location |
| D10 | emergency stop/guard |
| D11 | stall numbering/ID |
| D12 | wash hose point |

## 4. Roof views

| ID | View |
|---|---|
| R01 | roof top orthographic |
| R02 | ridge detail |
| R03 | solar array overview |
| R04 | solar maintenance path |
| R05 | gutter and downpipe |
| R06 | roof penetration/electrical route |

## 5. Technical overlay views

| ID | Overlay |
|---|---|
| T01 | water piping |
| T02 | manure flow |
| T03 | electrical/data |
| T04 | stormwater |
| T05 | combined utilities |
| T06 | floor slope arrows |
| T07 | airflow arrows |
| T08 | clean vs dirty zoning |

## 6. Context views

| ID | Context |
|---|---|
| C01 | shed + cow yard |
| C02 | shed + milk clean side |
| C03 | shed + feed side |
| C04 | shed + downstream waste route |
| C05 | shed within full 65 × 95 ft plant aerial |

## 7. Lighting/weather variants

For V06 and I01 at minimum, optionally produce:
- day
- dawn
- evening
- night
- monsoon exterior
- hot summer daylight

## 8. Generation order

When building the visual library:
1. V01 top orthographic
2. V06 SW aerial
3. V07 SE aerial
4. all elevations
5. I01/I02
6. scraper lane
7. cross-section
8. utility overlays
9. detail views
10. context views

This order establishes geometry before decorative/photorealistic images.

## 9. QA

Each image should be checked against:
- BLUEPRINT.md
- ARCHITECTURE.md
- UTILITIES.md
- agent visualization skill

Reject an image if it changes the design.
