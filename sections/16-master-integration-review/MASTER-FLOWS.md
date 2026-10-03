# Master Plant Flows

## Milk
```
Cow → milking → Section 03 → chiller → Section 14 → milk truck
```

## Feed
```
Truck → Section 14 → Section 06 → Section 05 → Section 01
```

## Manure
```
Section 01 → scraper/gutter → Section 07 → Section 08
```

## Gas
```
Section 08 → Section 09 → Section 10 → Section 11
```

## Digestate
```
Section 08 → Section 12 → solid + liquid fertilizer streams
```

## Water
```
Source → Section 13 → cows / milk / office / digester / process
```

## Electricity
```
Solar → main MDB/grid
Biogas generator → ATS → Essential Load Board
```

## Traffic
```
Gate → milk node → feed node → service/rear node → forward exit preferred
```

## Non-crossing laws
- Milk does not cross manure/digestate.
- Potable water does not cross-connect to dirty process lines.
- Raw gas never bypasses treatment.
- Solar does not energize isolated generator bus in baseline.
