---
DexID: '0675'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Arm Thrust|Arm Thrust]]'
- - Beginner
  - '[[SRD-Work Up|Work Up]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Karate Chop|Karate Chop]]'
- - Amateur
  - '[[SRD-Comet Punch|Comet Punch]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Circle Throw|Circle Throw]]'
- - Amateur
  - '[[SRD-Vital Throw|Vital Throw]]'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Entrainment|Entrainment]]'
- - Ace
  - '[[SRD-Parting Shot|Parting Shot]]'
- - Ace
  - '[[SRD-Sky Uppercut|Sky Uppercut]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Pro
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Pro
  - '[[SRD-Fire Punch|Fire Punch]]'
Name: Pancham
Species: '[[SRD-Pancham|Pancham]]'
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
