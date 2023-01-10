---
Moves:
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Master
  - '[[SRD-Scary Face|Scary Face]]'
- - Master
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Master
  - '[[SRD-Ice Beam|Ice Beam]]'
- - Master
  - '[[SRD-Origin Pulse|Origin Pulse]]'
- - Master
  - '[[SRD-Calm Mind|Calm Mind]]'
- - Master
  - '[[SRD-Muddy Water|Muddy Water]]'
- - Master
  - '[[SRD-Sheer Cold|Sheer Cold]]'
- - Master
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Master
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Master
  - '[[SRD-Water Spout|Water Spout]]'
- - Master
  - '[[SRD-Strength|Strength]]'
- - Master
  - '[[SRD-Dive|Dive]]'
- - Master
  - '[[SRD-Whirlpool|Whirlpool]]'
- - Master
  - '[[SRD-Psych Up|Psych Up]]'
- - Master
  - '[[SRD-Mist|Mist]]'
- - Master
  - '[[SRD-Splishy Splash|Splishy Splash]]'
- - Master
  - '[[SRD-Steam Eruption|Steam Eruption]]'
- - Master
  - '[[SRD-Defog|Defog]]'
- - Master
  - '[[SRD-Telekinesis|Telekinesis]]'
- - Master
  - '[[SRD-Blizzard|Blizzard]]'
- - Master
  - '[[SRD-Drain Punch|Drain Punch]]'
- - Master
  - '[[SRD-Snatch|Snatch]]'
Name: Kyogre (Primal Form)
Pokedex: '[[SRD-Kyogre (Primal Form)|Kyogre (Primal Form)]]'
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
