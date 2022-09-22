---
DexID: '0573'
Moves:
- - Beginner
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Beginner
  - '[[SRD-Tickle|Tickle]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bullet Seed|Bullet Seed]]'
- - Amateur
  - '[[SRD-Rock Blast|Rock Blast]]'
- - Amateur
  - '[[SRD-Sing|Sing]]'
- - Amateur
  - '[[SRD-Tail Slap|Tail Slap]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Pro
  - '[[SRD-Iron Tail|Iron Tail]]'
- - Pro
  - '[[SRD-Fake Tears|Fake Tears]]'
Name: Cinccino
Species: '[[SRD-Cinccino|Cinccino]]'
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
