---
Moves:
- - Starter
  - '[[SRD-Rest|Rest]]'
Name: Egg
Pokedex: '[[SRD-Egg|Egg]]'
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
