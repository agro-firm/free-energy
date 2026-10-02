---
name: manure-automation
description: Fully automatic transfer of dung/waste from cow shed to waste zone and digester.
---

# Manure Automation Skill

## Baseline mass
- Fresh dung: 300 kg/day.
- Collected at 90%: 270 kg/day.

## Process
Scraper → covered gutter/channel → receiving sump → debris/grit removal → mixing tank → measured water dosing → slurry pump → digester.

## Batch concept
At 1:1 dilution and 4 feeds/day:
- Dung per feed ≈ 67.5 kg.
- Water per feed ≈ 67.5 L.
- Slurry per feed ≈ 0.135 m³.
- Total slurry ≈ 0.54 m³/day.

## Required automation
- Scheduled scraper cycles.
- Sump high/low level.
- Mixer status.
- Water meter or dosing control.
- Feed-pump flow confirmation.
- Digester high-level inhibit.
- Pump overload and blockage alarm.
- Backflow prevention.

## Failure rule
Any full-digester, failed-pump, or blocked-line condition must stop upstream feed and alarm before the cow shed can flood.