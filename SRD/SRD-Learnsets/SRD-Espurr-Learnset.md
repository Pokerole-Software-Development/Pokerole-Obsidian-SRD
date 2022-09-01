---
DexID: '0676'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Covet|Covet]]'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Light Screen|Light Screen]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Fake Out|Fake Out]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Disarming Voice|Disarming Voice]]'
- - Ace
  - '[[SRD-Psyshock|Psyshock]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Signal Beam|Signal Beam]]'
- - Pro
  - '[[SRD-Barrier|Barrier]]'
- - Pro
  - '[[SRD-Yawn|Yawn]]'
Name: Espurr
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
