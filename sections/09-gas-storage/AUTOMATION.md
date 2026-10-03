# Gas Storage — Automation and Controls

## Primary controlled variable
Holder **volume/level percentage**.

Pressure is monitored for safety/diagnostics but is not the primary inventory measurement.

## Planning thresholds
- 20% = low cutout
- 30% = low warning
- 75% = downstream demand/generator-enable
- 90% = high warning
- 95% = high-high process action

Final thresholds may be tuned after commissioning.

## State logic
### EMPTY/LOW
If ≤20%:
- inhibit generator gas withdrawal
- Section 10 can remain standby
- alarm if continuing downward

### ACCUMULATING
20–75%:
- normal storage fill
- no forced generator start solely from level

### READY
≥75%:
- issue gas-available/demand-enable to Section 10/11
- start generation only if all downstream permissives are valid

### HIGH
≥90%:
- priority demand request
- operator advisory

### HIGH-HIGH
≥95%:
- request upstream feed reduction/hold
- verify flare/safe-vent readiness
- critical alarm if no downstream gas path

## Pressure interlocks
Vendor-specific:
- pressure low/vacuum approaching limit → close/stop withdrawal
- pressure high → stop inflow where safe and invoke engineered relief logic
- pressure high-high → critical shutdown/relief response

## Gas detector
High CH₄/H₂S:
- alarm
- inhibit nonessential electrical equipment as engineered
- stop hot work/entry
- isolate gas if safe
- emergency response

## Condensate
CT-301 high level:
- alarm
- stop transfer if liquid-slug risk exists
- drain safely

## Downstream generator cycle
Using current project numbers:
```
75%=6.0 m³
20%=1.6 m³
usable=4.4 m³
```

At ~2.23 m³/h:
```
runtime≈1.97 h
```

## Logging
- holder %
- calculated m³
- pressure
- fill rate
- withdrawal rate if meter available
- high/low events
- flare/vent events
- condensate drains
- gas detector alarms

## Hard safety
P/V protection remains mechanical and independent of automation.
