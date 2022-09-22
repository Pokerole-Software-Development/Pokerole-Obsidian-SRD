---
DexID: 0638
Moves:
- - Master
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Master
  - '[[SRD-Leer|Leer]]'
- - Master
  - '[[SRD-Double Kick|Double Kick]]'
- - Master
  - '[[SRD-Smack Down|Smack Down]]'
- - Master
  - '[[SRD-Safeguard|Safeguard]]'
- - Master
  - '[[SRD-Swift|Swift]]'
- - Master
  - '[[SRD-Take Down|Take Down]]'
- - Master
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Master
  - '[[SRD-Retaliate|Retaliate]]'
- - Master
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Master
  - '[[SRD-Sacred Sword|Sacred Sword]]'
- - Master
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Master
  - '[[SRD-Quick Guard|Quick Guard]]'
- - Master
  - '[[SRD-Work Up|Work Up]]'
- - Master
  - '[[SRD-Stone Edge|Stone Edge]]'
- - Master
  - '[[SRD-Close Combat|Close Combat]]'
- - Master
  - '[[SRD-Superpower|Superpower]]'
- - Master
  - '[[SRD-Giga Impact|Giga Impact]]'
- - Master
  - '[[SRD-Bulldoze|Bulldoze]]'
Name: Terrakion
Species: '[[SRD-Terrakion|Terrakion]]'
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
