---
DexID: '0650'
Moves:
- - Master
  - '[[SRD-Fell Stinger|Fell Stinger]]'
- - Master
  - '[[SRD-Techno Blast|Techno Blast]]'
- - Master
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Master
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Master
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Master
  - '[[SRD-Screech|Screech]]'
- - Master
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - Master
  - '[[SRD-Lock-On|Lock-On]]'
- - Master
  - '[[SRD-Flame Charge|Flame Charge]]'
- - Master
  - '[[SRD-Magnet Bomb|Magnet Bomb]]'
- - Master
  - '[[SRD-Slash|Slash]]'
- - Master
  - '[[SRD-Metal Sound|Metal Sound]]'
- - Master
  - '[[SRD-Signal Beam|Signal Beam]]'
- - Master
  - '[[SRD-Tri Attack|Tri Attack]]'
- - Master
  - '[[SRD-X-Scissor|X-Scissor]]'
- - Master
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - Master
  - '[[SRD-Simple Beam|Simple Beam]]'
- - Master
  - '[[SRD-Zap Cannon|Zap Cannon]]'
- - Master
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - Master
  - '[[SRD-Self Destruct|Self Destruct]]'
- - Master
  - '[[SRD-Flash Cannon|Flash Cannon]]'
- - Master
  - '[[SRD-Bullet Seed|Bullet Seed]]'
Name: Genesect
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
