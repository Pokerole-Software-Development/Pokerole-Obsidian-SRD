---
DexID: 0854
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
- - Amateur
  - '[[SRD-Octolock|Octolock]]'
- - Amateur
  - '[[SRD-Octazooka|Octazooka]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Reversal|Reversal]]'
- - Ace
  - '[[SRD-Superpower|Superpower]]'
- - Ace
  - '[[SRD-Topsy-Turvy|Topsy-Turvy]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Close Combat|Close Combat]]'
- - Pro
  - '[[SRD-Liquidation|Liquidation]]'
- - Pro
  - '[[SRD-Brutal Swing|Brutal Swing]]'
Name: Grapploct
Species: '[[SRD-Grapploct|Grapploct]]'
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
