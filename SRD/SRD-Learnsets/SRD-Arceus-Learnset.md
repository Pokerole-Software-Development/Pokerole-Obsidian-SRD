---
Moves:
- - Master
  - '[[SRD-Seismic Toss|Seismic Toss]]'
- - Master
  - '[[SRD-Cosmic Power|Cosmic Power]]'
- - Master
  - '[[SRD-Natural Gift|Natural Gift]]'
- - Master
  - '[[SRD-Punishment|Punishment]]'
- - Master
  - '[[SRD-Gravity|Gravity]]'
- - Master
  - '[[SRD-Earth Power|Earth Power]]'
- - Master
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - Master
  - '[[SRD-Extreme Speed|Extreme Speed]]'
- - Master
  - '[[SRD-Refresh|Refresh]]'
- - Master
  - '[[SRD-Future Sight|Future Sight]]'
- - Master
  - '[[SRD-Recover|Recover]]'
- - Master
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - Master
  - '[[SRD-Perish Song|Perish Song]]'
- - Master
  - '[[SRD-Judgment|Judgment]]'
- - Master
  - '[[SRD-Sunsteel Strike|Sunsteel Strike]]'
- - Master
  - '[[SRD-Infestation|Infestation]]'
- - Master
  - '[[SRD-Zap Cannon|Zap Cannon]]'
- - Master
  - '[[SRD-Draco Meteor|Draco Meteor]]'
- - Master
  - '[[SRD-Light Of Ruin|Light Of Ruin]]'
- - Master
  - '[[SRD-Inferno|Inferno]]'
- - Master
  - '[[SRD-Hurricane|Hurricane]]'
- - Master
  - '[[SRD-Phantom Force|Phantom Force]]'
- - Master
  - '[[SRD-Frenzy Plant|Frenzy Plant]]'
- - Master
  - '[[SRD-Detect|Detect]]'
- - Master
  - '[[SRD-Sheer Cold|Sheer Cold]]'
- - Master
  - '[[SRD-Sludge Wave|Sludge Wave]]'
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Origin Pulse|Origin Pulse]]'
Name: Arceus
Pokedex: '[[SRD-Arceus|Arceus]]'
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
