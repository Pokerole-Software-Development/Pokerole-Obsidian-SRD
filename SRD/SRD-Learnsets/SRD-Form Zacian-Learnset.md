---
DexID: 0889
Moves:
- - Master
  - '[[SRD-Sacred Sword|Sacred Sword]]'
- - Master
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Master
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Master
  - '[[SRD-Howl|Howl]]'
- - Master
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Master
  - '[[SRD-Bite|Bite]]'
- - Master
  - '[[SRD-Slash|Slash]]'
- - Master
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Master
  - '[[SRD-Iron Head|Iron Head]]'
- - Master
  - '[[SRD-Laser Focus|Laser Focus]]'
- - Master
  - '[[SRD-Crunch|Crunch]]'
- - Master
  - '[[SRD-Moonblast|Moonblast]]'
- - Master
  - '[[SRD-Close Combat|Close Combat]]'
- - Master
  - '[[SRD-Giga Impact|Giga Impact]]'
- - Master
  - '[[SRD-Air Slash|Air Slash]]'
- - Master
  - '[[SRD-Psycho Cut|Psycho Cut]]'
- - Master
  - '[[SRD-Solar Beam|Solar Beam]]'
- - Master
  - '[[SRD-Steel Beam|Steel Beam]]'
- - Master
  - '[[SRD-Behemoth Blade|Behemoth Blade]]'
Name: Form Zacian
Species: '[[SRD-Form Zacian|Form Zacian]]'
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
