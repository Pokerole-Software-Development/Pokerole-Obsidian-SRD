---
DexID: 0378
Moves:
- - Master
  - '[[SRD-Stomp|Stomp]]'
- - Master
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Master
  - '[[SRD-Charge Beam|Charge Beam]]'
- - Master
  - '[[SRD-Bulldoze|Bulldoze]]'
- - Master
  - '[[SRD-Curse|Curse]]'
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Amnesia|Amnesia]]'
- - Master
  - '[[SRD-Ice Beam|Ice Beam]]'
- - Master
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Master
  - '[[SRD-Lock-On|Lock-On]]'
- - Master
  - '[[SRD-Zap Cannon|Zap Cannon]]'
- - Master
  - '[[SRD-Superpower|Superpower]]'
- - Master
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - Master
  - '[[SRD-Explosion|Explosion]]'
- - Master
  - '[[SRD-Mimic|Mimic]]'
- - Master
  - '[[SRD-Avalanche|Avalanche]]'
- - Master
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Master
  - '[[SRD-Aurora Veil|Aurora Veil]]'
Name: Regice
Species: '[[SRD-Regice|Regice]]'
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
