---
DexID: '0151'
Moves:
- - Master
  - '[[SRD-Pound|Pound]]'
- - Master
  - '[[SRD-Reflect|Reflect]]'
- - Master
  - '[[SRD-Transform|Transform]]'
- - Master
  - '[[SRD-Mega Punch|Mega Punch]]'
- - Master
  - '[[SRD-Metronome|Metronome]]'
- - Master
  - '[[SRD-Psychic|Psychic]]'
- - Master
  - '[[SRD-Barrier|Barrier]]'
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Amnesia|Amnesia]]'
- - Master
  - '[[SRD-Me First|Me First]]'
- - Master
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Master
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Master
  - '[[SRD-Aura Sphere|Aura Sphere]]'
- - Master
  - '[[SRD-Any Move|Any Move]]'
Name: Mew
Species: '[[SRD-Mew|Mew]]'
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
