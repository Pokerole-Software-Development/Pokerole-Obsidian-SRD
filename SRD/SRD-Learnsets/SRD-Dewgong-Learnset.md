---
DexID: 0087
Moves:
- - Starter
  - '[[SRD-Signal Beam|Signal Beam]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Encore|Encore]]'
- - Beginner
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Beginner
  - '[[SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Ice Shard|Ice Shard]]'
- - Amateur
  - '[[SRD-Rest|Rest]]'
- - Amateur
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Amateur
  - '[[SRD-Aurora Beam|Aurora Beam]]'
- - Amateur
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - Amateur
  - '[[SRD-Brine|Brine]]'
- - Amateur
  - '[[SRD-Sheer Cold|Sheer Cold]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Dive|Dive]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Ace
  - '[[SRD-Ice Beam|Ice Beam]]'
- - Ace
  - '[[SRD-Safeguard|Safeguard]]'
- - Ace
  - '[[SRD-Hail|Hail]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Avalanche|Avalanche]]'
- - Pro
  - '[[SRD-Perish Song|Perish Song]]'
- - Pro
  - '[[SRD-Horn Drill|Horn Drill]]'
Name: Dewgong
Species: '[[SRD-Dewgong|Dewgong]]'
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
