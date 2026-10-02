# Cow Yard — AI Image Generation Guide

## Geometry lock
18 ft wide × 28 ft long. Active yard 18 × 24 ft, service/drain strip 18 × 4 ft. Shade canopy 12 × 18 ft.

## Camera coordinate system
X 0–28 west→east, Y 0–18 south→north, Z up.

### Top orthographic
camera (14,9,55), target (14,9,0).

### West / shed connection
camera (-35,9,7), target (14,9,4).

### East / drain side
camera (63,9,7), target (14,9,3).

### South
camera (14,-35,7), target (14,9,4).

### North
camera (14,53,7), target (14,9,4).

### SW aerial
camera (-20,-20,28), target (14,9,3).

### SE aerial
camera (48,-20,28), target (14,9,3).

### NW aerial
camera (-20,38,28), target (14,9,3).

### NE aerial
camera (48,38,28), target (14,9,3).

## Photoreal prompt template
Create a photorealistic Section 02 Cow Yard for PLANT-V1.0 in Bangladesh. Exact footprint 28 ft long × 18 ft wide. Show only 10 cows in the yard. West half includes a practical 12 × 18 ft open-sided shade canopy; next 12 × 18 ft is open paved exercise area; east 4 × 18 ft is service/drain strip with trough and dirty linear drain. Non-slip concrete, galvanized fence, cattle gate toward cow shed, clean practical farm environment. No biogas or generator equipment.

## Blueprint prompt
Create an orthographic engineering blueprint of an 18 × 28 ft cow yard. Dimension shade 12 × 18, open zone 12 × 18 and service strip 4 × 18. Show slope arrows toward east drain, trough, gates, fence, XYZ axes and 10-cow operational capacity.

## Drainage overlay
Show uncovered yard dirty runoff in brown/orange to east drain. Show canopy roof runoff separately in light blue to clean stormwater. Do not send all rain directly to digester.

## Rain image
Show monsoon rain on open half, clean canopy gutter working, dirty yard drain flowing without flooding, cows under shade or returned to shed.

## Negative prompt
No 20 cows simultaneously, no grass pasture, no mud, no gas equipment, no generator, no fertilizer system, no enclosed room.
