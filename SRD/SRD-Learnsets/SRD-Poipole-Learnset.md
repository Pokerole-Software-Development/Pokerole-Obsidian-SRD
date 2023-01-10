---
Moves:
- - Master
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Master
  - '[[SRD-Peck|Peck]]'
- - Master
  - '[[SRD-Growl|Growl]]'
- - Master
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Master
  - '[[SRD-Acid|Acid]]'
- - Master
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Master
  - '[[SRD-Venoshock|Venoshock]]'
- - Master
  - '[[SRD-Charm|Charm]]'
- - Master
  - '[[SRD-Venom Drench|Venom Drench]]'
- - Master
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Master
  - '[[SRD-Poison Jab|Poison Jab]]'
- - Master
  - '[[SRD-Toxic|Toxic]]'
- - Master
  - '[[SRD-Fell Stinger|Fell Stinger]]'
- - Master
  - '[[SRD-Gastro Acid|Gastro Acid]]'
- - Master
  - '[[SRD-Iron Tail|Iron Tail]]'
- - Master
  - '[[SRD-Signal Beam|Signal Beam]]'
Name: Poipole
Pokedex: '[[SRD-Poipole|Poipole]]'
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
