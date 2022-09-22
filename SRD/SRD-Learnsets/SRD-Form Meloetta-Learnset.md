---
DexID: 0648
Moves:
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
  - '[[SRD-Entrainment|Entrainment]]'
- - Master
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Master
  - '[[SRD-Revelation Dance|Revelation Dance]]'
- - Master
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - Master
  - '[[SRD-Captivate|Captivate]]'
Name: Form Meloetta
Species: '[[SRD-Form Meloetta|Form Meloetta]]'
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
