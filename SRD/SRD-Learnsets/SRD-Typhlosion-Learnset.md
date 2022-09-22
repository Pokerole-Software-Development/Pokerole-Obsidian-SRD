---
DexID: '0157'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Smokescreen|Smokescreen]]'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Amateur
  - '[[SRD-Flame Wheel|Flame Wheel]]'
- - Amateur
  - '[[SRD-Flame Charge|Flame Charge]]'
- - Amateur
  - '[[SRD-Swift|Swift]]'
- - Amateur
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Amateur
  - '[[SRD-Lava Plume|Lava Plume]]'
- - Amateur
  - '[[SRD-Rollout|Rollout]]'
- - Amateur
  - '[[SRD-Gyro Ball|Gyro Ball]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Inferno|Inferno]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Eruption|Eruption]]'
- - Ace
  - '[[SRD-Burn Up|Burn Up]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Blast Burn|Blast Burn]]'
- - Pro
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Pro
  - '[[SRD-Thunder Punch|Thunder Punch]]'
Name: Typhlosion
Species: '[[SRD-Typhlosion|Typhlosion]]'
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
