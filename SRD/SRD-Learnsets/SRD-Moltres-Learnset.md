---
Moves:
- - Master
  - '[[SRD-Wing Attack|Wing Attack]]'
- - Master
  - '[[SRD-Ember|Ember]]'
- - Master
  - '[[SRD-Fire Spin|Fire Spin]]'
- - Master
  - '[[SRD-Agility|Agility]]'
- - Master
  - '[[SRD-Endure|Endure]]'
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Master
  - '[[SRD-Safeguard|Safeguard]]'
- - Master
  - '[[SRD-Air Slash|Air Slash]]'
- - Master
  - '[[SRD-Sunny Day|Sunny Day]]'
- - Master
  - '[[SRD-Heat Wave|Heat Wave]]'
- - Master
  - '[[SRD-Solar Beam|Solar Beam]]'
- - Master
  - '[[SRD-Sky Attack|Sky Attack]]'
- - Master
  - '[[SRD-Roost|Roost]]'
- - Master
  - '[[SRD-Hurricane|Hurricane]]'
- - Master
  - '[[SRD-Burn Up|Burn Up]]'
- - Master
  - '[[SRD-Will-O-Wisp|Will-O-Wisp]]'
- - Master
  - '[[SRD-Flame Charge|Flame Charge]]'
- - Master
  - '[[SRD-Curse|Curse]]'
- - Master
  - '[[SRD-Fire Blast|Fire Blast]]'
- - Master
  - '[[SRD-Swift|Swift]]'
- - Master
  - '[[SRD-Fly|Fly]]'
Name: Moltres
Pokedex: '[[SRD-Moltres|Moltres]]'
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
