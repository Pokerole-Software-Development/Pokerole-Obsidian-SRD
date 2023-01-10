---
Moves:
- - Master
  - '[[SRD-Scratch|Scratch]]'
- - Master
  - '[[SRD-Spark|Spark]]'
- - Master
  - '[[SRD-Hone Claws|Hone Claws]]'
- - Master
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Master
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Master
  - '[[SRD-Volt Switch|Volt Switch]]'
- - Master
  - '[[SRD-Snarl|Snarl]]'
- - Master
  - '[[SRD-Fake Out|Fake Out]]'
- - Master
  - '[[SRD-Charge|Charge]]'
- - Master
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Master
  - '[[SRD-Slash|Slash]]'
- - Master
  - '[[SRD-Wild Charge|Wild Charge]]'
- - Master
  - '[[SRD-Quick Guard|Quick Guard]]'
- - Master
  - '[[SRD-Plasma Fists|Plasma Fists]]'
- - Master
  - '[[SRD-Close Combat|Close Combat]]'
- - Master
  - '[[SRD-Discharge|Discharge]]'
- - Master
  - '[[SRD-Fire Punch|Fire Punch]]'
- - Master
  - '[[SRD-Drain Punch|Drain Punch]]'
- - Master
  - '[[SRD-Dual Chop|Dual Chop]]'
Name: Zeraora
Pokedex: '[[SRD-Zeraora|Zeraora]]'
---

#PokeroleSRD/Learnsets

## `= this.Name` Learnset

**Pokedex Entry:** `= this.Pokedex`

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1] AS Move
FROM #PokeroleSRD/Learnsets
flatten moves as T
where file.path = this.file.path
```
