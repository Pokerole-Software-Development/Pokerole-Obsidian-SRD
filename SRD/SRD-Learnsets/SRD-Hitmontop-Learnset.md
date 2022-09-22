---
DexID: '0237'
Moves:
- - Starter
  - '[[SRD-Revenge|Revenge]]'
- - Starter
  - '[[SRD-Rolling Kick|Rolling Kick]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[SRD-Triple Kick|Triple Kick]]'
- - Amateur
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - Amateur
  - '[[SRD-Counter|Counter]]'
- - Amateur
  - '[[SRD-Feint|Feint]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Gyro Ball|Gyro Ball]]'
- - Amateur
  - '[[SRD-Quick Guard|Quick Guard]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Ace
  - '[[SRD-Detect|Detect]]'
- - Ace
  - '[[SRD-Close Combat|Close Combat]]'
- - Ace
  - '[[SRD-Endeavor|Endeavor]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Mach Punch|Mach Punch]]'
- - Pro
  - '[[SRD-High Jump Kick|High Jump Kick]]'
- - Pro
  - '[[SRD-Twister|Twister]]'
Name: Hitmontop
Species: '[[SRD-Hitmontop|Hitmontop]]'
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
