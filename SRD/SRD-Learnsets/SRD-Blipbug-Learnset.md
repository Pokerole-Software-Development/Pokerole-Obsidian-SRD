---
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
Pokedex: '[[SRD-Blipbug|Blipbug]]'
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
