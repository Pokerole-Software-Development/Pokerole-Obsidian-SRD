---
DexID: 0531M1
Moves:
- - Starter
  - '[[SRD-Play Nice|Play Nice]]'
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Helping Hand|Helping Hand]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - Beginner
  - '[[SRD-Misty Terrain|Misty Terrain]]'
- - Beginner
  - '[[SRD-Refresh|Refresh]]'
- - Beginner
  - '[[SRD-Baby-Doll Eyes|Baby-Doll Eyes]]'
- - Beginner
  - '[[SRD-Double Slap|Double Slap]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Disarming Voice|Disarming Voice]]'
- - Amateur
  - '[[SRD-Secret Power|Secret Power]]'
- - Amateur
  - '[[SRD-Attract|Attract]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Entrainment|Entrainment]]'
- - Amateur
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-After You|After You]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Simple Beam|Simple Beam]]'
- - Ace
  - '[[SRD-Last Resort|Last Resort]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Draining Kiss|Draining Kiss]]'
- - Pro
  - '[[SRD-Wish|Wish]]'
- - Pro
  - '[[SRD-Heal Bell|Heal Bell]]'
Name: Mega-Audino
Species: '[[SRD-Mega-Audino|Mega-Audino]]'
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
