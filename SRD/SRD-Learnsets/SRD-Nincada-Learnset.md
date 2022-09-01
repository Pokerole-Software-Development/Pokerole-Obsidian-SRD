---
DexID: 0290
Moves:
- - Starter
  - '[[SRD-Harden|Harden]]'
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Leech Life|Leech Life]]'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Mind Reader|Mind Reader]]'
- - Amateur
  - '[[SRD-False Swipe|False Swipe]]'
- - Amateur
  - '[[SRD-Bide|Bide]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Ace
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Ace
  - '[[SRD-Dig|Dig]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Silver Wind|Silver Wind]]'
- - Pro
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Pro
  - '[[SRD-Endure|Endure]]'
Name: Nincada
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
