---
DexID: '0674'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Work Up|Work Up]]'
- - Beginner
  - '[[SRD-Arm Thrust|Arm Thrust]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bullet Punch|Bullet Punch]]'
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
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Entrainment|Entrainment]]'
- - Ace
  - '[[SRD-Parting Shot|Parting Shot]]'
- - Ace
  - '[[SRD-Sky Uppercut|Sky Uppercut]]'
- - Ace
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Ace
  - '[[SRD-Taunt|Taunt]]'
- - Ace
  - '[[SRD-Low Sweep|Low Sweep]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
- - Pro
  - '[[SRD-Focus Punch|Focus Punch]]'
- - Pro
  - '[[SRD-Drain Punch|Drain Punch]]'
Name: Pangoro
Species: '[[SRD-Pangoro|Pangoro]]'
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
