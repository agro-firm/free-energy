# Master Process

## Milk process
```
Cow
→ milking
→ Section 03 receive/test
→ cooling
→ clean storage
→ sanitary dispatch
→ Section 14
→ buyer
```

## Feed process
```
Feed truck
→ Section 14
→ Section 06 covered unload
→ Section 05 dry storage
→ ration issue
→ Section 01 cows
```

## Manure/slurry process
```
Section 01 scraper/gutter
→ Section 07 screen/receiving
→ measured dilution
→ mixing/batching
→ Section 08 digester
```

Planning:
- 270 kg/day collected dung.
- 270 L/day dilution.
- 0.54 m³/day slurry.
- ~4 batches/day.

## Gas process
```
Section 08 raw biogas
→ condensate/PV protection
→ Section 09 holder
→ Section 10 H₂S + moisture + metering/regulation
→ Section 11 generator
```

Never:
```
raw gas → generator
```

## Digestate/fertilizer
```
Section 08 digestate
→ Section 12 buffer
→ screw press
→ solid cake
→ curing/drying
→ screening/bagging

pressate
→ covered liquid tank
→ approved farm/dispatch use
```

## Water
```
source
→ Section 13 8 m³ ground tank
→ twin pumps
→ pressure header
→ users + 2 m³ overhead tank
```

Priority:
1. cow drinking.
2. milk hygiene.
3. handwash/vet.
4. digester minimum.
5. process.
6. noncritical wash.

## Electricity
Normal:
```
Grid + Section 15 solar → Main MDB → plant loads
```

Backup:
```
Section 11 biogas generator → ATS → Essential Load Board
```

Baseline does not parallel on-grid solar with isolated generator.

## Data/controls
Local PLC/sensors:
Sections 07–15 as applicable.

Master:
- alarms.
- daily totals.
- water.
- gas.
- generator.
- solar.
- milk.
- fertilizer.
- maintenance.
- business KPI.
