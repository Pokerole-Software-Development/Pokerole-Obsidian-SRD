---
DexID: '0753'
Moves:
- - Starter
  - '[[SRD-Water Sport|Water Sport]]'
- - Starter
  - '[[SRD-Bubble|Bubble]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Infestation|Infestation]]'
- - Beginner
  - '[[SRD-Spider Web|Spider Web]]'
- - Beginner
  - '[[SRD-Bug Bite|Bug Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Soak|Soak]]'
- - Amateur
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Amateur
  - '[[SRD-Leech Life|Leech Life]]'
- - Amateur
  - '[[SRD-Mirror Coat|Mirror Coat]]'
- - Amateur
  - '[[SRD-Lunge|Lunge]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Liquidation|Liquidation]]'
- - Ace
  - '[[SRD-Entrainment|Entrainment]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Power Split|Power Split]]'
- - Pro
  - '[[SRD-Attract|Attract]]'
- - Pro
  - '[[SRD-Scald|Scald]]'
Name: Araquanid
Species: '[[SRD-Araquanid|Araquanid]]'
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
