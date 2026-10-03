# Master Interfaces

| From | To | Interface | Critical rule |
|---|---|---|---|
| 01 | 03 | cow/milk transfer | clean controlled path |
| 01 | 07 | manure | direct dirty transfer |
| 01 | 13 | water | drinking priority |
| 01 | 15 | roof/solar | structural signoff |
| 02 | 13 | trough/wash | dirty runoff separate |
| 03 | 14 | milk dispatch | clean lane node |
| 03 | 11 | backup power | motor-start/load check |
| 03 | 13 | potable cleaning | potable-quality water |
| 05 | 06 | feed | covered dry transfer |
| 06 | 14 | truck | one truck at a time |
| 07 | 08 | slurry | ~0.54 m³/day metered |
| 07 | 13 | dilution water | ~270 L/day planning |
| 08 | 09 | raw gas | pressure/condensate safety |
| 08 | 12 | digestate | contained transfer |
| 09 | 10 | raw gas | no bypass |
| 10 | 11 | treated gas | H₂S/moisture/pressure compliant |
| 11 | plant | essential power | ATS / no backfeed |
| 12 | 14 | fertilizer dispatch | no dirty spill |
| 13 | users | water | backflow protection |
| 14 | 03/06/11/12 | logistics | keep clear |
| 15 | MDB/grid | solar AC | anti-islanding |

## Final interface record
Each final interface must show:
- source tag.
- destination tag.
- pipe/cable/road size.
- design capacity.
- isolation.
- ownership boundary.
- control signal if any.
- commissioning test.
- as-built coordinate.

## Change law
Changing one interface requires review of both connected sections and the root master documents.
