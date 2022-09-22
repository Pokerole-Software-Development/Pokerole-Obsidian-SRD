---
DexID: '0760'
Moves:
- - Starter
  - '[[SRD-Splash|Splash]]'
- - Starter
  - '[[SRD-Play Nice|Play Nice]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - Beginner
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Beginner
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Magical Leaf|Magical Leaf]]'
- - Amateur
  - '[[SRD-Teeter Dance|Teeter Dance]]'
- - Amateur
  - '[[SRD-Flail|Flail]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Aromatic Mist|Aromatic Mist]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Charm|Charm]]'
- - Pro
  - '[[SRD-Play Rough|Play Rough]]'
- - Pro
  - '[[SRD-Acupressure|Acupressure]]'
Name: Bounsweet
Species: '[[SRD-Bounsweet|Bounsweet]]'
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
