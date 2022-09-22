---
DexID: '0717'
Moves:
- - Starter
  - '[[SRD-Endure|Endure]]'
Name: Zygarde Cell
Species: '[[SRD-Zygarde Cell|Zygarde Cell]]'
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
