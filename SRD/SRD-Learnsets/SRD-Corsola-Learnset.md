---
DexID: '0222'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Harden|Harden]]'
- - Beginner
  - '[[SRD-Bubble|Bubble]]'
- - Beginner
  - '[[SRD-Recover|Recover]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Refresh|Refresh]]'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - Amateur
  - '[[SRD-Spike Cannon|Spike Cannon]]'
- - Amateur
  - '[[SRD-Brine|Brine]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Rock Blast|Rock Blast]]'
- - Amateur
  - '[[SRD-Endure|Endure]]'
- - Amateur
  - '[[SRD-Power Gem|Power Gem]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Ace
  - '[[SRD-Mirror Coat|Mirror Coat]]'
- - Ace
  - '[[SRD-Earth Power|Earth Power]]'
- - Ace
  - '[[SRD-Flail|Flail]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Head Smash|Head Smash]]'
- - Pro
  - '[[SRD-Screech|Screech]]'
- - Pro
  - '[[SRD-Whirlpool|Whirlpool]]'
Name: Corsola
Species: '[[SRD-Corsola|Corsola]]'
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
