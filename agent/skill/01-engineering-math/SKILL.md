---
name: engineering-math
description: Mandatory mathematics, units, measurement, geometry and capacity rules for every project decision.
---

# Engineering Math Skill

## Required solution format
Every calculation must show:
1. Given values.
2. Unknown.
3. Assumptions.
4. Formula.
5. Unit substitution.
6. Exact or unrounded result.
7. Rounded design result.
8. Capacity or safety margin.
9. What must be field, vendor, or engineer verified.

## Unit laws
- 1 ft = 0.3048 m.
- 1 in = 25.4 mm.
- 1 ft² = 0.09290304 m².
- 1 m² = 10.7639 ft².
- 1 acre = 43,560 ft² = 4,046.856 m².
- 1 m³ = 1,000 L.

## Geometry
- Rectangle area: A = L × W.
- Rectangular volume: V = L × W × H.
- Cylinder: V = πr²h.
- Slope percent: rise ÷ run × 100.

## Space law
Sum of all buildings, yards, lanes, drainage, safety and maintenance clearances must be less than or equal to 6,175 ft².
Report utilization percent = allocated area ÷ 6,175 × 100.

## Coordinate law
Use origin at southwest/front-left of the site unless a surveyed plan changes it.
Store each object as x, y, width, depth, and height when known.
Check x + width ≤ plot width and y + depth ≤ plot depth.
Check pairwise overlap unless overlap is intentional, such as solar above the shed.

## Manure
fresh_dung = cows × dung_per_cow_per_day.
collected_dung = fresh_dung × collection_efficiency.
Baseline: 20 × 15 = 300 kg/day; 300 × 0.90 = 270 kg/day.

## Slurry and digester
For 1:1 dilution, planning water mass ≈ dung mass.
slurry_mass = dung + water.
daily_slurry_volume = slurry_mass ÷ assumed slurry density.
working_volume = daily_slurry_volume × HRT.
Always state dilution ratio, density and HRT assumptions.

## Biogas
gas_day = collected_dung × gas_yield.
Baseline low: 270 × 0.030 = 8.10 m³/day.
Baseline good-operation case: 270 × 0.034 = 9.18 m³/day.

## Gas to electricity
biogas_LHV ≈ methane_fraction × methane_LHV.
electricity_per_m3 = biogas_LHV × generator_efficiency.
daily_kWh = gas_day × electricity_per_m3.
runtime_h = daily_kWh ÷ operating_kW.

## Gas storage
usable_gas = holder_volume × (high_setpoint - low_setpoint).
runtime_per_cycle = usable_gas ÷ gas_consumption_per_hour.

## Solar
array_kWp = panel_count × panel_W ÷ 1000.
daily_energy = array_kWp × verified_site_specific_yield.

## Water
daily_water = cow_drinking + washdown + digester_dilution + staff/process.
storage_days = usable_storage ÷ daily_water.

## Milk
milk_day = lactating_cows × average_L_per_cow_day.
milk_month = milk_day × operating_days.

## Feed
feed_day = sum of headcount × ration per head.
storage_mass = feed_day × storage_days.
storage_volume = storage_mass ÷ actual bulk density.

## Financial
revenue = quantity × selling price.
operating_profit = revenue - operating cost.
simple_payback = CAPEX ÷ annual cash benefit.

## Dimension law
Every component report should state length, width, clear height, overall height, footprint, capacity, service clearance, and inlet/outlet position when known.

## Concept height defaults for visualization only
- Cow shed: eave about 12 ft and ridge about 16–18 ft, ASSUMPTION only.
- Milk/office/generator/fertilizer rooms: about 10 ft clear, ASSUMPTION only.
- Feed store: about 12 ft clear, ASSUMPTION only.
- Digester, gas holder and equipment heights: VENDOR values only.

## Value tags
Use FIXED, CALCULATED, ASSUMPTION, VENDOR, or REGULATORY for important values.

## Math gate
No design or image change is accepted until relevant geometry and capacity calculations pass.