---
Moves:
- - Starter
  - '[[SRD-Endure|Endure]]'
Name: Zygarde Cell
Pokedex: '[[SRD-Zygarde Cell|Zygarde Cell]]'
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
