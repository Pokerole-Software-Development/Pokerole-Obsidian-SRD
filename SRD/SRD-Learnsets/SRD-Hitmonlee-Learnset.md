---
Moves:
- - Starter
  - '[[SRD-Double Kick|Double Kick]]'
- - Starter
  - '[[SRD-Revenge|Revenge]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Meditate|Meditate]]'
- - Beginner
  - '[[SRD-Rolling Kick|Rolling Kick]]'
- - Beginner
  - '[[SRD-Jump Kick|Jump Kick]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Brick Break|Brick Break]]'
- - Amateur
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Amateur
  - '[[SRD-Feint|Feint]]'
- - Amateur
  - '[[SRD-High Jump Kick|High Jump Kick]]'
- - Amateur
  - '[[SRD-Mind Reader|Mind Reader]]'
- - Amateur
  - '[[SRD-Foresight|Foresight]]'
- - Amateur
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Amateur
  - '[[SRD-Blaze Kick|Blaze Kick]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Endure|Endure]]'
- - Ace
  - '[[SRD-Mega Kick|Mega Kick]]'
- - Ace
  - '[[SRD-Close Combat|Close Combat]]'
- - Ace
  - '[[SRD-Reversal|Reversal]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Bounce|Bounce]]'
- - Pro
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - Pro
  - '[[SRD-Mach Punch|Mach Punch]]'
Name: Hitmonlee
Pokedex: '[[SRD-Hitmonlee|Hitmonlee]]'
---

#PokeroleSRD/Learnsets

## `= this.Name` Learnset

**Pokedex Entry:** `= this.Pokedex`

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1] AS Move
FROM #PokeroleSRD/Learnsets
flatten moves as T
where file.path = this.file.path
```
