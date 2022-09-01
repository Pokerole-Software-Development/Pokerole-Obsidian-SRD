---
DexID: 0491
Moves:
- - Master
  - '[[SRD-Ominous Wind|Ominous Wind]]'
- - Master
  - '[[SRD-Disable|Disable]]'
- - Master
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Master
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Master
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Master
  - '[[SRD-Nightmare|Nightmare]]'
- - Master
  - '[[SRD-Double Team|Double Team]]'
- - Master
  - '[[SRD-Haze|Haze]]'
- - Master
  - '[[SRD-Dark Void|Dark Void]]'
- - Master
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Master
  - '[[SRD-Dream Eater|Dream Eater]]'
- - Master
  - '[[SRD-Dark Pulse|Dark Pulse]]'
- - Master
  - '[[SRD-Torment|Torment]]'
- - Master
  - '[[SRD-Wonder Room|Wonder Room]]'
- - Master
  - '[[SRD-Foul Play|Foul Play]]'
- - Master
  - '[[SRD-Spite|Spite]]'
Name: Darkrai
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
