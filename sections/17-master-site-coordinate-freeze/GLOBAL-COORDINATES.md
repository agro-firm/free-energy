# Global Coordinates — DCF-1

## Datum
Plan coordinates are feet.

- P0=(0,0): southwest/front.
- P1=(65,0): southeast/front.
- P2=(65,95): northeast/rear.
- P3=(0,95): northwest/rear.

## Master axes
- X0–51 = plant/building field.
- X51–65 = service lane.
- Y0 = public-road/front assumption.
- Y95 = rear boundary.

## Orientation
Global rotation of a section is allowed where listed, but its own internal local blueprint remains unchanged.

## Section register
| Sec | Section | X min–max | Y min–max | Global size | Orientation |
|---:|---|---|---|---|---|
| 04 | Office/vet | 0–12 | 0–15 | 12×15 | native |
| 13 | Water utility | 12–20 | 0–12 | 8×12 | native |
| 05 | Feed store | 21–41 | 0–18 | 20×18 | rotated |
| 06 | Feed canopy | 41–51 | 0–18 | 10×18 | native |
| 01 | Cow shed | 0–26 | 18–66 | 26×48 | native |
| 03 | Milk room | 37–51 | 18–36 | 14×18 | native |
| 07 | Waste receiving | 26–40 | 37–47 | 14×10 | rotated |
| 08 | Digester compound | 26–46 | 47–63 | 20×16 | rotated |
| 11 | Generator/electrical | 39–51 | 65–79 | 12×14 | native |
| 02 | Cow yard | 0–18 | 66–94 | 18×28 | native |
| 09 | Gas storage | 18–28 | 66–78 | 10×12 | native |
| 10 | Gas treatment | 28–38 | 66–74 | 10×8 | rotated |
| 12 | Fertilizer | 29–51 | 79–95 | 22×16 | rotated |
| 14 | Service lane | 51–65 | 0–95 | 14×95 | fixed |
| 15 | Solar | Section 01 roof | — | 15 kWp | rooftop |

## Boundary result
All rectangles remain inside X0–65 / Y0–95.
