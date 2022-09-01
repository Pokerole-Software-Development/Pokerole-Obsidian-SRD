---
DexID: 0385
Moves:
- - Starter
  - '[[SRD-Wish|Wish]]'
- - Starter
  - '[[SRD-Doom Desire|Doom Desire]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Meteor Mash|Meteor Mash]]'
- - Pro
  - '[[SRD-Swift|Swift]]'
- - Pro
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Pro
  - '[[SRD-Psychic|Psychic]]'
- - Pro
  - '[[SRD-Refresh|Refresh]]'
- - Pro
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - Pro
  - '[[SRD-Rest|Rest]]'
- - Pro
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Pro
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Pro
  - '[[SRD-Gravity|Gravity]]'
- - Pro
  - '[[SRD-Healing Wish|Healing Wish]]'
- - Pro
  - '[[SRD-Future Sight|Future Sight]]'
- - Pro
  - '[[SRD-Cosmic Power|Cosmic Power]]'
- - Pro
  - '[[SRD-Last Resort|Last Resort]]'
- - Pro
  - '[[SRD-Confusion|Confusion]]'
- - Pro
  - '[[SRD-Confide|Confide]]'
- - Pro
  - '[[SRD-Trick|Trick]]'
- - Pro
  - '[[SRD-Trick Room|Trick Room]]'
Name: Jirachi
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
