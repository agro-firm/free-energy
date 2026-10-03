# Water Utility — Functional Design

## Philosophy
The utility provides both **bulk autonomy** and **pressure reliability**.

### Ground tank
Main reserve.
Protects farm from short source interruptions.

### Overhead tank
- emergency gravity reserve
- pressure buffer
- keeps cow drinking available during short power outages

### Duty/standby pumps
Two 1 HP pumps:
- one duty
- one standby
- alternate runtime
- automatic failover

## Distribution
Normal:
ground tank → pump manifold → farm distribution + OHT refill.

Power loss:
OHT → gravity bypass → priority drinking/essential branches.

## Pressure zones
### Gravity
Use for:
- trough refill
- emergency handwash
- low-pressure essential supply

### Boosted
Use for:
- wash hose
- milk-room cleaning
- digester dosing
- process cleaning

## Water treatment
Treatment is based on actual lab results, not assumed.

Possible modules:
- sediment filtration
- iron/manganese removal
- arsenic removal
- chlorination
- UV
- activated carbon

RO is not a default farm-wide solution.

## Cross-connection control
No hose or dirty process line may siphon back into potable network.
Use:
- air gaps
- check valves
- backflow preventers where appropriate
