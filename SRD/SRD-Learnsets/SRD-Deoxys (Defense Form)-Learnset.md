---
Moves:
- - Master
  - '[[SRD-Leer|Leer]]'
- - Master
  - '[[SRD-Wrap|Wrap]]'
- - Master
  - '[[SRD-Night Shade|Night Shade]]'
- - Master
  - '[[SRD-Teleport|Teleport]]'
- - Master
  - '[[SRD-Knock Off|Knock Off]]'
- - Master
  - '[[SRD-Spikes|Spikes]]'
- - Master
  - '[[SRD-Psychic|Psychic]]'
- - Master
  - '[[SRD-Snatch|Snatch]]'
- - Master
  - '[[SRD-Psycho Shift|Psycho Shift]]'
- - Master
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Master
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Master
  - '[[SRD-Amnesia|Amnesia]]'
- - Master
  - '[[SRD-Psycho Boost|Psycho Boost]]'
- - Master
  - '[[SRD-Recover|Recover]]'
- - Master
  - '[[SRD-Counter|Counter]]'
- - Master
  - '[[SRD-Mirror Coat|Mirror Coat]]'
- - Master
  - '[[SRD-Bind|Bind]]'
- - Master
  - '[[SRD-Signal Beam|Signal Beam]]'
Name: Deoxys (Defense Form)
Pokedex: '[[SRD-Deoxys (Defense Form)|Deoxys (Defense Form)]]'
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
