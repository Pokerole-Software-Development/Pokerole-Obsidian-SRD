---
Moves:
- - Starter
  - '[[SRD-Transform|Transform]]'
Name: Ditto
Pokedex: '[[SRD-Ditto|Ditto]]'
---

#PokeroleSRD/Learnsets

## `= this.Name` Learnset

**Pokedex Entry:** `= this.Pokedex`

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1] AS Move
FROM #PokeroleSRD/Learnsets
flatten moves as T
where file.path = this.file.path
```
