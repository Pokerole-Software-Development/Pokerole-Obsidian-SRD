---
DexID: 0283
Moves:
- - Starter
  - '[[SRD-Bubble|Bubble]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Water Sport|Water Sport]]'
- - Amateur
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Amateur
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Haze|Haze]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Mist|Mist]]'
- - Ace
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Ace
  - '[[SRD-Sticky Web|Sticky Web]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Signal Beam|Signal Beam]]'
- - Pro
  - '[[SRD-Mud Shot|Mud Shot]]'
- - Pro
  - '[[SRD-Hydro Pump|Hydro Pump]]'
Name: Surskit
Species: '[[SRD-Surskit|Surskit]]'
---

#PokeroleSRD/Learnsets

## `= this.Name` Learnset

**DexID:** `= this.DexID`

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1] AS Move
FROM #PokeroleSRD/Learnsets
flatten moves as T
where file.path = this.file.path
```
