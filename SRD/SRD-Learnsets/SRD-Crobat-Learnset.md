---
DexID: 0169
Moves:
- - Starter
  - '[[SRD-Absorb|Absorb]]'
- - Starter
  - '[[SRD-Screech|Screech]]'
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - Starter
  - '[[SRD-Supersonic|Supersonic]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Wing Attack|Wing Attack]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Swift|Swift]]'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Acrobatics|Acrobatics]]'
- - Amateur
  - '[[SRD-Air Cutter|Air Cutter]]'
- - Amateur
  - '[[SRD-Mean Look|Mean Look]]'
- - Amateur
  - '[[SRD-Leech Life|Leech Life]]'
- - Amateur
  - '[[SRD-Poison Fang|Poison Fang]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Cross Poison|Cross Poison]]'
- - Ace
  - '[[SRD-Haze|Haze]]'
- - Ace
  - '[[SRD-Air Slash|Air Slash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Brave Bird|Brave Bird]]'
- - Pro
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Pro
  - '[[SRD-Heat Wave|Heat Wave]]'
Name: Crobat
Species: '[[SRD-Crobat|Crobat]]'
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
