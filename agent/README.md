# Free Energy Project — AI Agent Guide

This file tells any AI, engineer-assistant, coding agent or image-generation agent how to work on this repository without changing the approved plant accidentally.

## Project identity

This repository defines a compact integrated **20-cow dairy + manure automation + biogas + fertilizer + generator + rooftop solar** plant.

The current baseline is controlled by:

- `agent/skill/00-master-plant/SKILL.md`
- `agent/skill/01-engineering-math/SKILL.md`

Those two files are mandatory before making any design decision.

## Mandatory workflow for every AI

Before doing any work:

1. Read `00-master-plant`.
2. Read `01-engineering-math`.
3. Read the skill for every subsystem affected.
4. Read the matching `sections/<section>/README.md` when the task concerns a physical area.
5. If creating or editing an image, also read `15-visualization-images`.
6. If changing dimensions, capacity, layout, equipment or process flow, run the checks in `18-construction-review`.
7. Never use an image as the only source of engineering truth.
8. Never silently change a FIXED value.

## Current locked baseline

- Plot: **65 × 95 ft**
- 20 adult cows
- Cow shed: **26 × 48 ft**
- Cow yard: **18 × 28 ft**
- Milk room + chiller: **14 × 18 ft**
- Feed store: **18 × 20 ft**
- Waste receiving/mixing: **~140 ft²**
- Digester: **25 m³**
- Raw gas holder: **8 m³**
- Gas treatment zone: **8 × 10 ft**
- Generator room: **12 × 14 ft**
- Generator: **5 kW rated**
- Fertilizer zone: **16 × 22 ft**
- Water utility: **8 × 12 ft**
- Service lane: **14 ft wide**
- Solar: **15 kWp on cow-shed roof**

## Canonical process order

### Manure and gas
Cow shed → Automatic scraper/gutter → Waste receiving → Mixing/dosing → Digester → Raw gas storage → Gas treatment → Generator

### Digestate
Digester → Separator → Solid fertilizer + Liquid fertilizer

### Milk
Cow → Milking → Milk room/chiller → Clean dispatch door → Service lane → Milk truck

### Feed
Truck → Feed unloading canopy → Feed store → Cow shed

No AI may reorder these flows without an approved redesign and recalculation.

# Skill catalog

## 00 — Master Plant
**File:** `agent/skill/00-master-plant/SKILL.md`

Use this first for every task.

It defines:
- current dimensions
- equipment capacities
- process order
- non-negotiable rules
- the approved project baseline

If another document conflicts with this file, the master plant wins unless a new approved change updates it.

## 01 — Engineering Math
**File:** `agent/skill/01-engineering-math/SKILL.md`

Use for:
- all measurements
- area calculations
- volume calculations
- height/width/length decisions
- manure calculations
- digester sizing
- gas production
- generator sizing/runtime
- solar sizing
- water
- feed
- milk
- financial calculations

Required format:

Given → Unknown → Assumptions → Formula → Units → Exact result → Rounded design value → Margin → Verification required

Important values must be labeled:
- **FIXED**
- **CALCULATED**
- **ASSUMPTION**
- **VENDOR**
- **REGULATORY**

## 02 — Site Layout
**File:** `agent/skill/02-site-layout/SKILL.md`

Use for:
- moving sections
- checking plot fit
- creating coordinates
- adjacency
- access routes
- avoiding overlap
- reducing unused space

Every apparent open space needs a reason such as truck movement, drainage, maintenance, fire access, washing or ventilation.

## 03 — Cow Shed
**File:** `agent/skill/03-cow-shed/SKILL.md`

Use for:
- cow stalls
- feed alley
- drinking
- fans/ventilation
- roof
- floor
- manure gutter
- scraper interface
- cow-shed interior images

Do not shrink animal space just to fit utilities.

## 04 — Manure Automation
**File:** `agent/skill/04-manure-automation/SKILL.md`

Use for:
- automatic scraper
- manure channels
- receiving sump
- mixer
- water dosing
- feed pump
- batch sequence
- level sensors
- fault handling

Current planning flow is around 270 kg/day collected dung and approximately 0.54 m³/day diluted slurry.

## 05 — Biogas Digester
**File:** `agent/skill/05-biogas-digester/SKILL.md`

Use for:
- digester process
- HRT
- volume
- feed/discharge
- mixing
- access
- conceptual layout

Current nominal digester is **25 m³**.

Vessel structural details must come from a vendor/engineer.

## 06 — Gas Storage + Treatment
**File:** `agent/skill/06-gas-storage-treatment/SKILL.md`

Use for:
- raw gas holder
- condensate
- H₂S treatment
- moisture separator
- gas metering
- pressure regulation
- isolation valves
- flare/vent concepts

Current raw gas holder is **8 m³**.

Required order:
Digester → Storage → Treatment → Generator.

## 07 — Generator + Electrical
**File:** `agent/skill/07-generator-electrical/SKILL.md`

Use for:
- biogas generator
- generator room
- electrical output
- runtime
- ATS
- distribution
- exhaust
- emergency stop

Current generator is **5 kW rated**, normally planned around approximately 4 kW operating output when gas is available.

## 08 — Solar
**File:** `agent/skill/08-solar/SKILL.md`

Use for:
- panel quantity
- roof packing
- inverter
- solar yield
- structural load
- cable/string calculations
- solar images

Current target is **15 kWp** on the cow-shed roof.

## 09 — Milk + Cold Chain
**File:** `agent/skill/09-milk-cold-chain/SKILL.md`

Use for:
- milking transfer
- chiller
- milk room
- hygiene
- wash/CIP
- dispatch
- truck pickup
- milk-room images

Clean milk traffic must stay separate from manure traffic.

## 10 — Feed Logistics
**File:** `agent/skill/10-feed-logistics/SKILL.md`

Use for:
- feed store
- feed inventory
- delivery frequency
- unloading
- feed route
- storage capacity

The compact site is designed for frequent deliveries, not months of fodder storage.

## 11 — Fertilizer + Digestate
**File:** `agent/skill/11-fertilizer-digestate/SKILL.md`

Use for:
- screw press/separation
- liquid digestate
- solid fertilizer
- curing
- drying
- bagging
- dispatch

Do not claim a guaranteed N-P-K value or fertilizer yield without real testing.

## 12 — Water + Drainage
**File:** `agent/skill/12-water-drainage/SKILL.md`

Use for:
- water tank
- pumps
- daily demand
- drinking water
- wash water
- clean storm drainage
- dirty/process drainage

Keep stormwater and manure/process drainage separate.

## 13 — Truck / Service Lane
**File:** `agent/skill/13-truck-service-lane/SKILL.md`

Use for:
- milk truck
- feed truck
- fertilizer loading
- service access
- emergency access
- gate and turning checks

Current service lane is **14 ft wide**.

## 14 — Controls + Automation
**File:** `agent/skill/14-controls-automation/SKILL.md`

Use for:
- PLC logic
- scraper scheduling
- pump control
- gas-holder logic
- generator start/stop
- alarms
- sensors
- data logging

Software safety logic never replaces physical relief or safety hardware.

## 15 — Visualization / Images
**File:** `agent/skill/15-visualization-images/SKILL.md`

Use every time an image is requested.

Supported images include:
- top view
- true plan
- aerial view
- 30°, 45°, 60° views
- north/south/east/west
- NE/NW/SE/SW
- front/rear
- truck-lane view
- cutaway
- cow-shed interior
- milk-room interior
- feed unloading
- manure system
- digester
- gas holder
- gas treatment
- generator room
- fertilizer zone
- water system
- solar roof

### Image rule
Before image generation:
1. identify the plant version
2. list visible sections
3. read their skills
4. preserve dimensions and adjacency
5. choose camera direction/height
6. use the established flow colors when making an engineering diagram
7. verify the generated image against the master plan

An image must never become a new engineering design simply because it looks attractive.

## 16 — Safety + Regulatory
**File:** `agent/skill/16-safety-regulatory/SKILL.md`

Use for:
- gas safety
- H₂S
- fire
- electrical
- confined space
- generator exhaust
- local permits
- Bangladesh authority checks

Never invent legal separation distances or regulatory requirements.

## 17 — Cost + Profit
**File:** `agent/skill/17-cost-profit/SKILL.md`

Use for:
- CAPEX
- monthly OPEX
- milk revenue
- fertilizer revenue
- energy savings
- profit
- payback

Always separate cash revenue from electricity savings.

## 18 — Construction + Review
**File:** `agent/skill/18-construction-review/SKILL.md`

Use before accepting:
- a new plan
- changed dimensions
- changed equipment
- changed process order
- changed capacity
- a construction phase

This skill performs the final area, flow, capacity, safety, cost and image-consistency review.

# Physical section documentation

All physical plant areas are documented under:

`sections/`

Each section contains:
- `README.md` — purpose, baseline, interfaces and future work
- `images/` — approved section images and future detail images

When generating a section image, save or document it against the relevant section. Do not mix unrelated section images in another section's folder.

# Rules for future AI work

- Never guess a missing dimension and present it as fixed.
- Never change a dimension in an image without changing the engineering baseline first.
- Never remove safety/maintenance space and call it "unused".
- Never calculate equipment from floor area alone; calculate from process capacity.
- Always preserve clean milk flow and dirty manure flow separation.
- Always calculate before resizing equipment.
- Always update the master skill if an approved major change changes the canonical plant.
- Always update the matching section README when that section's approved design changes.
