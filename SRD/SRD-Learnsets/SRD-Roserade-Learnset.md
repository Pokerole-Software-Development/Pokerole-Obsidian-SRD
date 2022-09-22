---
DexID: '0407'
Moves:
- - Beginner
  - '[[SRD-Poison Sting|Poison Sting]]'
- - Beginner
  - '[[SRD-Grassy Terrain|Grassy Terrain]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Weather Ball|Weather Ball]]'
- - Amateur
  - '[[SRD-Venom Drench|Venom Drench]]'
- - Amateur
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Amateur
  - '[[SRD-Magical Leaf|Magical Leaf]]'
- - Amateur
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Pro
  - '[[SRD-Leaf Storm|Leaf Storm]]'
- - Pro
  - '[[SRD-Pin Missile|Pin Missile]]'
Name: Roserade
Species: '[[SRD-Roserade|Roserade]]'
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
