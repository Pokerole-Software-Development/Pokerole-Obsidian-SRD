---
DexID: '0301'
Moves:
- - Starter
  - '[[SRD-Fake Out|Fake Out]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Attract|Attract]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Double Slap|Double Slap]]'
- - Amateur
  - '[[SRD-Sing|Sing]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Pro
  - '[[SRD-Wish|Wish]]'
- - Pro
  - '[[SRD-Cosmic Power|Cosmic Power]]'
Name: Delcatty
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
