---
DexID: 0825
Moves:
- - Starter
  - '[[SRD-Struggle Bug|Struggle Bug]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Sticky Web|Sticky Web]]'
- - Pro
  - '[[SRD-Supersonic|Supersonic]]'
- - Pro
  - '[[SRD-Infestation|Infestation]]'
Name: Blipbug
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
