---
DexID: '0741'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Bubble|Bubble]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Rock Smash|Rock Smash]]'
- - Beginner
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Beginner
  - '[[SRD-Pursuit|Pursuit]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Amateur
  - '[[SRD-Power-Up Punch|Power-Up Punch]]'
- - Amateur
  - '[[SRD-Dizzy Punch|Dizzy Punch]]'
- - Amateur
  - '[[SRD-Avalanche|Avalanche]]'
- - Amateur
  - '[[SRD-Reversal|Reversal]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Ice Hammer|Ice Hammer]]'
- - Ace
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Ace
  - '[[SRD-Dynamic Punch|Dynamic Punch]]'
- - Ace
  - '[[SRD-Close Combat|Close Combat]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Endeavor|Endeavor]]'
- - Pro
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Pro
  - '[[SRD-Superpower|Superpower]]'
Name: Crabominable
Species: '[[SRD-Crabominable|Crabominable]]'
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
