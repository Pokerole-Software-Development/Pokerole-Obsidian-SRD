---
DexID: 0562G
Moves:
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - Starter
  - '[[SRD-Protect|Protect]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Haze|Haze]]'
- - Beginner
  - '[[SRD-Night Shade|Night Shade]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Disable|Disable]]'
- - Amateur
  - '[[SRD-Brutal Swing|Brutal Swing]]'
- - Amateur
  - '[[SRD-Crafty Shield|Crafty Shield]]'
- - Amateur
  - '[[SRD-Hex|Hex]]'
- - Amateur
  - '[[SRD-Mean Look|Mean Look]]'
- - Amateur
  - '[[SRD-Slam|Slam]]'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - Amateur
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Power Split|Power Split]]'
- - Ace
  - '[[SRD-Guard Split|Guard Split]]'
- - Ace
  - '[[SRD-Destiny Bond|Destiny Bond]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Sandstorm|Sandstorm]]'
- - Pro
  - '[[SRD-Psychic|Psychic]]'
- - Pro
  - '[[SRD-Memento|Memento]]'
Name: Galarian Yamask
Species: '[[SRD-Galarian Yamask|Galarian Yamask]]'
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
