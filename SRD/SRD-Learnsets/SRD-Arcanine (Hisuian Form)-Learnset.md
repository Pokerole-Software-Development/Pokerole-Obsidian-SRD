---
Moves:
- - Starter
  - '[[SRD-Roar|Roar]]'
- - Starter
  - '[[SRD-Ember|Ember]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - Amateur
  - '[[SRD-Flame Wheel|Flame Wheel]]'
- - Amateur
  - '[[SRD-Accelerock|Accelerock]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Ace
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Ace
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Ace
  - '[[SRD-Work Up|Work Up]]'
- - Ace
  - '[[SRD-Power Gem|Power Gem]]'
- - Ace
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Ace
  - '[[SRD-Lava Plume|Lava Plume]]'
- - Ace
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Ace
  - '[[SRD-Raging Fury|Raging Fury]]'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Morning Sun|Morning Sun]]'
- - Ace
  - '[[SRD-Flare Blitz|Flare Blitz]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Outrage|Outrage]]'
- - Pro
  - '[[SRD-Scorching Sands|Scorching Sands]]'
- - Pro
  - '[[SRD-Meteor Beam|Meteor Beam]]'
- - Pro
  - '[[SRD-Wild Charge|Wild Charge]]'
Name: Arcanine (Hisuian Form)
Pokedex: '[[SRD-Arcanine (Hisuian Form)|Arcanine (Hisuian Form)]]'
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
