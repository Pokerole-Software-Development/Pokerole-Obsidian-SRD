---
DexID: 0851
Moves:
- - Starter
  - '[[SRD-Rock Smash|Rock Smash]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Feint|Feint]]'
- - Beginner
  - '[[SRD-Bind|Bind]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Detect|Detect]]'
- - Amateur
  - '[[SRD-Brick Break|Brick Break]]'
- - Amateur
  - '[[SRD-Bulk Up|Bulk Up]]'
- - Amateur
  - '[[SRD-Submission|Submission]]'
- - Amateur
  - '[[SRD-Taunt|Taunt]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Reversal|Reversal]]'
- - Ace
  - '[[SRD-Superpower|Superpower]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Soak|Soak]]'
- - Pro
  - '[[SRD-Circle Throw|Circle Throw]]'
- - Pro
  - '[[SRD-Seismic Toss|Seismic Toss]]'
Name: Clobbopus
Species: '[[SRD-Clobbopus|Clobbopus]]'
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
