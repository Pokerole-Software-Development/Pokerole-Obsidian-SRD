---
DexID: '0423'
Moves:
- - Starter
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Starter
  - '[[SRD-Mud Sport|Mud Sport]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Harden|Harden]]'
- - Beginner
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Beginner
  - '[[SRD-Mud Bomb|Mud Bomb]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Hidden Power|Hidden Power]]'
- - Amateur
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - Amateur
  - '[[SRD-Muddy Water|Muddy Water]]'
- - Amateur
  - '[[SRD-Recover|Recover]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Acid Armor|Acid Armor]]'
- - Pro
  - '[[SRD-Counter|Counter]]'
- - Pro
  - '[[SRD-Fissure|Fissure]]'
Name: Gastrodon
Species: '[[SRD-Gastrodon|Gastrodon]]'
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
