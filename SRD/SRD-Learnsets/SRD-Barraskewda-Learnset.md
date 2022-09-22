---
DexID: 0846
Moves:
- - Starter
  - '[[SRD-Peck|Peck]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Throat Chop|Throat Chop]]'
- - Amateur
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Dive|Dive]]'
- - Amateur
  - '[[SRD-Laser Focus|Laser Focus]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Liquidation|Liquidation]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Night Slash|Night Slash]]'
- - Pro
  - '[[SRD-Poison Jab|Poison Jab]]'
- - Pro
  - '[[SRD-Giga Impact|Giga Impact]]'
Name: Barraskewda
Species: '[[SRD-Barraskewda|Barraskewda]]'
---

#PokeroleSRD/Learnsets

## `= this.Name` Learnset

**DexID:** `= this.DexID`

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1] AS Move
FROM #PokeroleSRD/Learnsets
flatten moves as T
where file.path = this.file.path
```
