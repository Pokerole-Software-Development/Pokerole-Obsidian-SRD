---
DexID: 0875
Moves:
- - Starter
  - '[[SRD-Stored Power|Stored Power]]'
- - Starter
  - '[[SRD-Play Nice|Play Nice]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Encore|Encore]]'
- - Beginner
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Beginner
  - '[[SRD-Disarming Voice|Disarming Voice]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Amateur
  - '[[SRD-Follow Me|Follow Me]]'
- - Amateur
  - '[[SRD-After You|After You]]'
- - Amateur
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Calm Mind|Calm Mind]]'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Power Split|Power Split]]'
- - Ace
  - '[[SRD-Guard Split|Guard Split]]'
- - Ace
  - '[[SRD-Last Resort|Last Resort]]'
- - Ace
  - '[[SRD-Healing Wish|Healing Wish]]'
- - Ace
  - '[[SRD-Psychic Terrain|Psychic Terrain]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Fake Out|Fake Out]]'
- - Pro
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - Pro
  - '[[SRD-Wonder Room|Wonder Room]]'
Name: Indeedee
Species: '[[SRD-Indeedee|Indeedee]]'
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
