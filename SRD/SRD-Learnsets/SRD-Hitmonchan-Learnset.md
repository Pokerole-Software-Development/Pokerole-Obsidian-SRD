---
DexID: '0107'
Moves:
- - Starter
  - '[[SRD-Revenge|Revenge]]'
- - Starter
  - '[[SRD-Comet Punch|Comet Punch]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Agility|Agility]]'
- - Beginner
  - '[[SRD-Pursuit|Pursuit]]'
- - Beginner
  - '[[SRD-Mach Punch|Mach Punch]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bullet Punch|Bullet Punch]]'
- - Amateur
  - '[[SRD-Feint|Feint]]'
- - Amateur
  - '[[SRD-Vacuum Wave|Vacuum Wave]]'
- - Amateur
  - '[[SRD-Quick Guard|Quick Guard]]'
- - Amateur
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Amateur
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Amateur
  - '[[SRD-Fire Punch|Fire Punch]]'
- - Amateur
  - '[[SRD-Sky Uppercut|Sky Uppercut]]'
- - Amateur
  - '[[SRD-Mega Punch|Mega Punch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Detect|Detect]]'
- - Ace
  - '[[SRD-Focus Punch|Focus Punch]]'
- - Ace
  - '[[SRD-Counter|Counter]]'
- - Ace
  - '[[SRD-Close Combat|Close Combat]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - Pro
  - '[[SRD-Drain Punch|Drain Punch]]'
- - Pro
  - '[[SRD-High Jump Kick|High Jump Kick]]'
Name: Hitmonchan
Species: '[[SRD-Hitmonchan|Hitmonchan]]'
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
