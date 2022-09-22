---
DexID: 0186
Moves:
- - Starter
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Beginner
  - '[[SRD-Double Slap|Double Slap]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Perish Song|Perish Song]]'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - Amateur
  - '[[SRD-Bounce|Bounce]]'
- - Amateur
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - Amateur
  - '[[SRD-Mud Shot|Mud Shot]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Icy Wind|Icy Wind]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Refresh|Refresh]]'
Name: Politoed
Species: '[[SRD-Politoed|Politoed]]'
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
