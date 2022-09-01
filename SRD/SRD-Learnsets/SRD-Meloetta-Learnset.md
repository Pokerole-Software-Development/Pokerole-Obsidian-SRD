---
DexID: 0648F1
Moves:
- - Master
  - '[[SRD-Psychic|Psychic]]'
- - Master
  - '[[SRD-Round|Round]]'
- - Master
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Master
  - '[[SRD-Confusion|Confusion]]'
- - Master
  - '[[SRD-Sing|Sing]]'
- - Master
  - '[[SRD-Teeter Dance|Teeter Dance]]'
- - Master
  - '[[SRD-Acrobatics|Acrobatics]]'
- - Master
  - '[[SRD-Psybeam|Psybeam]]'
- - Master
  - '[[SRD-Echoed Voice|Echoed Voice]]'
- - Master
  - '[[SRD-U-Turn|U-Turn]]'
- - Master
  - '[[SRD-Psychic|Psychic]]'
- - Master
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - Master
  - '[[SRD-Role Play|Role Play]]'
- - Master
  - '[[SRD-Close Combat|Close Combat]]'
- - Master
  - '[[SRD-Perish Song|Perish Song]]'
- - Master
  - '[[SRD-Boomburst|Boomburst]]'
- - Master
  - '[[SRD-Disarming Voice|Disarming Voice]]'
- - Master
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - Master
  - '[[SRD-Relic Song|Relic Song]]'
- - Master
  - '[[SRD-Captivate|Captivate]]'
Name: Meloetta
---

#PokeroleSRD/Learnsets

## `= this.Name` Learnset

**DexID:** `= this.DexID`

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1] AS Move
FROM "Pokerole SRD/SRD-Learnsets"
flatten moves as T
where file.path = this.file.path
```
