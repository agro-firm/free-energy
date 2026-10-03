# Generator + Electrical — Concept Single-Line

## Topology
```text
UTILITY / NORMAL FARM SOURCE
          |
       MAIN MDB
          |
      NORMAL FEED
          |
        ATS-501 -------------------------------+
          |                                    |
          |                               GEN BREAKER
          |                                    |
          |                                 5 kW GEN
          |
      ELP-501 ESSENTIAL LOAD BOARD
          |
  +-------+---------+---------+---------+
  |                 |         |         |
Milk Chiller    Controls   Water    Critical
   etc.          / ICT     Pump     Lighting
```

## Generator branch
```text
5 kW Generator
   |
32 A 2P breaker
   |
multifunction meter
   |
ATS emergency input
```

## Normal branch
Normal farm source may eventually be:
- grid-fed MDB
- grid + solar inverter MDB
- approved hybrid-inverter backup output

Section 15 finalizes solar topology.

## ATS
- 2-pole switching concept
- mechanically/electrically interlocked
- break-before-make
- no backfeed
- rated 40 A minimum; 63 A standard-size hardware acceptable
- generator still protected by 32 A breaker

## Protection
Concept:
- generator breaker
- ATS
- ELP main isolator
- branch MCB/RCBO/RCD as appropriate
- Type 2 SPD
- earth-fault protection
- generator over/under voltage
- over/under frequency
- overcurrent
- engine shutdowns

## Neutral and earth
Neutral switching and neutral-earth bonding depend on generator winding, ATS topology and farm earthing system.

A licensed electrical engineer must define:
- switched/unswitched neutral
- generator neutral bond
- RCD reference
- earth electrode/bonding
- fault-loop impedance

## Solar anti-islanding
Unless a future approved hybrid system supports generator paralleling, solar inverter must not energize the generator island.

No uncontrolled AC coupling.
