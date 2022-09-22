---
DexID: '0360'
Moves:
- - Starter
  - '[[SRD-Charm|Charm]]'
- - Starter
  - '[[SRD-Encore|Encore]]'
- - Starter
  - '[[SRD-Splash|Splash]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Counter|Counter]]'
- - Amateur
  - '[[SRD-Destiny Bond|Destiny Bond]]'
- - Amateur
  - '[[SRD-Mirror Coat|Mirror Coat]]'
- - Amateur
  - '[[SRD-Safeguard|Safeguard]]'
Name: Wynaut
Species: '[[SRD-Wynaut|Wynaut]]'
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
