---
DexID: 0819
Moves:
- - Starter
  - '[[SRD-Snipe Shot|Snipe Shot]]'
- - Starter
  - '[[SRD-Acrobatics|Acrobatics]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Pound|Pound]]'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Water Gun|Water Gun]]'
- - Amateur
  - '[[SRD-Bind|Bind]]'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Tearful Look|Tearful Look]]'
- - Amateur
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-U-Turn|U-Turn]]'
- - Ace
  - '[[SRD-Liquidation|Liquidation]]'
- - Ace
  - '[[SRD-Soak|Soak]]'
- - Ace
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Ice Shard|Ice Shard]]'
- - Pro
  - '[[SRD-Fell Stinger|Fell Stinger]]'
- - Pro
  - '[[SRD-Hydro Cannon|Hydro Cannon]]'
Name: Inteleon
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
