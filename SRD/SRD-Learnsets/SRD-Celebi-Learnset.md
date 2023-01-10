---
Moves:
- - Master
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Master
  - '[[SRD-Confusion|Confusion]]'
- - Master
  - '[[SRD-Recover|Recover]]'
- - Master
  - '[[SRD-Heal Bell|Heal Bell]]'
- - Master
  - '[[SRD-Safeguard|Safeguard]]'
- - Master
  - '[[SRD-Magical Leaf|Magical Leaf]]'
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Master
  - '[[SRD-Natural Gift|Natural Gift]]'
- - Master
  - '[[SRD-Heal Block|Heal Block]]'
- - Master
  - '[[SRD-Future Sight|Future Sight]]'
- - Master
  - '[[SRD-Healing Wish|Healing Wish]]'
- - Master
  - '[[SRD-Leaf Storm|Leaf Storm]]'
- - Master
  - '[[SRD-Perish Song|Perish Song]]'
- - Master
  - '[[SRD-Double Team|Double Team]]'
- - Master
  - '[[SRD-Trick Room|Trick Room]]'
- - Master
  - '[[SRD-Nature Power|Nature Power]]'
- - Master
  - '[[SRD-Worry Seed|Worry Seed]]'
Name: Celebi
Pokedex: '[[SRD-Celebi|Celebi]]'
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
