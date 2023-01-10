---
Moves:
- - Starter
  - '[[SRD-Teleport|Teleport]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Mimic|Mimic]]'
- - Ace
  - '[[SRD-Signal Beam|Signal Beam]]'
- - Ace
  - '[[SRD-Metronome|Metronome]]'
Name: Abra
Pokedex: '[[SRD-Abra|Abra]]'
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
