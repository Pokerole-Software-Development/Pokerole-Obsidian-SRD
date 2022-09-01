---
DexID: '0243'
Moves:
- - Master
  - '[[SRD-Bite|Bite]]'
- - Master
  - '[[SRD-Leer|Leer]]'
- - Master
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - Master
  - '[[SRD-Roar|Roar]]'
- - Master
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Master
  - '[[SRD-Spark|Spark]]'
- - Master
  - '[[SRD-Reflect|Reflect]]'
- - Master
  - '[[SRD-Crunch|Crunch]]'
- - Master
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Master
  - '[[SRD-Discharge|Discharge]]'
- - Master
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Master
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Master
  - '[[SRD-Calm Mind|Calm Mind]]'
- - Master
  - '[[SRD-Thunder|Thunder]]'
- - Master
  - '[[SRD-Double Team|Double Team]]'
- - Master
  - '[[SRD-Substitute|Substitute]]'
- - Master
  - '[[SRD-Volt Switch|Volt Switch]]'
- - Master
  - '[[SRD-Flash|Flash]]'
- - Master
  - '[[SRD-Mimic|Mimic]]'
- - Master
  - '[[SRD-Curse|Curse]]'
- - Master
  - '[[SRD-Shock Wave|Shock Wave]]'
Name: Raikou
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
