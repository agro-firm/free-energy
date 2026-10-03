# Master Interface Matrix

| From | To | Interface | Critical rule |
|---|---|---|---|
| 01 Cow shed | 03 Milk | milk path | clean only |
| 01 | 07 Waste | dung scraper/gutter | dirty only |
| 01 | 13 Water | drinking/wash | drinking priority |
| 01 | 15 Solar | roof structure | structural signoff |
| 02 Yard | 13 Water | trough/wash | runoff separate |
| 03 Milk | 14 Lane | milk pickup | no dirty crossing |
| 03 | 11 Essential power | chiller backup | motor start checked |
| 03 | 13 Water | potable cleaning | potable quality |
| 05 Feed | 06 Canopy | feed transfer | dry/weather protected |
| 06 | 14 Lane | truck unload | one truck at a time |
| 07 Waste | 08 Digester | 0.54 m³/day slurry | metered batches |
| 07 | 13 Water | dilution | ~270 L/day |
| 08 Digester | 09 Gas | raw biogas | condensate/PV safety |
| 08 | 12 Fertilizer | digestate | ~0.54 m³/day |
| 09 Gas | 10 Treatment | raw gas | no generator bypass |
| 10 Treatment | 11 Generator | treated gas | H₂S/moisture/pressure |
| 11 Generator | Essential board | backup power | no grid backfeed |
| 12 Fertilizer | 14 Lane | dispatch | no dirty spill |
| 13 Water | all users | clean water | backflow protection |
| 14 Lane | 03/06/12 | logistics | no permanent storage |
| 15 Solar | Main MDB/grid | AC power | no uncontrolled genset parallel |

## Mandatory interface drawing
Each interface above must have:
- source tag.
- destination tag.
- size/capacity.
- isolation point.
- ownership boundary.
- commissioning test.
