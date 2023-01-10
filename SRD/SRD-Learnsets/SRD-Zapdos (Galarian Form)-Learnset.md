---
Moves:
- - Master
  - '[[SRD-Peck|Peck]]'
- - Master
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Master
  - '[[SRD-Rock Smash|Rock Smash]]'
- - Master
  - '[[SRD-Light Screen|Light Screen]]'
- - Master
  - '[[SRD-Pluck|Pluck]]'
- - Master
  - '[[SRD-Agility|Agility]]'
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Brick Break|Brick Break]]'
- - Master
  - '[[SRD-Drill Peck|Drill Peck]]'
- - Master
  - '[[SRD-Quick Guard|Quick Guard]]'
- - Master
  - '[[SRD-Thunderous Kick|Thunderous Kick]]'
- - Master
  - '[[SRD-Bulk Up|Bulk Up]]'
- - Master
  - '[[SRD-Counter|Counter]]'
- - Master
  - '[[SRD-Detect|Detect]]'
- - Master
  - '[[SRD-Close Combat|Close Combat]]'
- - Master
  - '[[SRD-Reversal|Reversal]]'
- - Master
  - '[[SRD-Brave Bird|Brave Bird]]'
- - Master
  - '[[SRD-Stomping Tantrum|Stomping Tantrum]]'
- - Master
  - '[[SRD-Blaze Kick|Blaze Kick]]'
Name: Zapdos (Galarian Form)
Pokedex: '[[SRD-Zapdos (Galarian Form)|Zapdos (Galarian Form)]]'
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
