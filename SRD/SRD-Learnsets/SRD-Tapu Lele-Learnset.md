---
Moves:
- - Master
  - '[[SRD-Psychic Terrain|Psychic Terrain]]'
- - Master
  - '[[SRD-Aromatic Mist|Aromatic Mist]]'
- - Master
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - Master
  - '[[SRD-Mean Look|Mean Look]]'
- - Master
  - '[[SRD-Draining Kiss|Draining Kiss]]'
- - Master
  - '[[SRD-Astonish|Astonish]]'
- - Master
  - '[[SRD-Withdraw|Withdraw]]'
- - Master
  - '[[SRD-Confusion|Confusion]]'
- - Master
  - '[[SRD-Psywave|Psywave]]'
- - Master
  - '[[SRD-Skill Swap|Skill Swap]]'
- - Master
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Master
  - '[[SRD-Psyshock|Psyshock]]'
- - Master
  - '[[SRD-Tickle|Tickle]]'
- - Master
  - '[[SRD-Nature''s Madness|Nature''s Madness]]'
- - Master
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Master
  - '[[SRD-Flatter|Flatter]]'
- - Master
  - '[[SRD-Moonblast|Moonblast]]'
- - Master
  - '[[SRD-Magic Room|Magic Room]]'
- - Master
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Master
  - '[[SRD-Wonder Room|Wonder Room]]'
- - Master
  - '[[SRD-Telekinesis|Telekinesis]]'
Name: Tapu Lele
Pokedex: '[[SRD-Tapu Lele|Tapu Lele]]'
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
