---
DexID: '0201'
Moves:
- - Starter
  - '[[SRD-Hidden Power|Hidden Power]]'
Name: Unown
Species: '[[SRD-Unown|Unown]]'
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
