---
DexID: 0800F3
Moves:
- - Master
  - '[[SRD-Crafty Shield|Crafty Shield]]'
- - Master
  - '[[SRD-Gear Up|Gear Up]]'
- - Master
  - '[[SRD-Shift Gear|Shift Gear]]'
- - Master
  - '[[SRD-Iron Head|Iron Head]]'
- - Master
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Master
  - '[[SRD-Sonic Boom|Sonic Boom]]'
- - Master
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Master
  - '[[SRD-Psybeam|Psybeam]]'
- - Master
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - Master
  - '[[SRD-Aurora Beam|Aurora Beam]]'
- - Master
  - '[[SRD-Mirror Shot|Mirror Shot]]'
- - Master
  - '[[SRD-Mind Reader|Mind Reader]]'
- - Master
  - '[[SRD-Flash Cannon|Flash Cannon]]'
- - Master
  - '[[SRD-Fleur Cannon|Fleur Cannon]]'
- - Master
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Master
  - '[[SRD-Pain Split|Pain Split]]'
- - Master
  - '[[SRD-Synchronoise|Synchronoise]]'
- - Master
  - '[[SRD-Aura Sphere|Aura Sphere]]'
- - Master
  - '[[SRD-Heart Swap|Heart Swap]]'
- - Master
  - '[[SRD-Trump Card|Trump Card]]'
- - Master
  - '[[SRD-Heal Bell|Heal Bell]]'
- - Master
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Master
  - '[[SRD-Dazzling Gleam|Dazzling Gleam]]'
Name: Magearna
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
