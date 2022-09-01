---
DexID: 0849
Moves:
- - Starter
  - '[[SRD-Nuzzle|Nuzzle]]'
- - Starter
  - '[[SRD-Tearful Look|Tearful Look]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Flail|Flail]]'
- - Beginner
  - '[[SRD-Acid|Acid]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Belch|Belch]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Encore|Encore]]'
- - Pro
  - '[[SRD-Rest|Rest]]'
- - Pro
  - '[[SRD-Round|Round]]'
Name: Toxel
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
