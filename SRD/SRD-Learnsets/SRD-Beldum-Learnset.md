---
DexID: '0374'
Moves:
- - Starter
  - '[[SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Iron Head|Iron Head]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Headbutt|Headbutt]]'
Name: Beldum
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
