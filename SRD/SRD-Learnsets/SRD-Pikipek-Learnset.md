---
DexID: '0730'
Moves:
- - Starter
  - '[[SRD-Peck|Peck]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Echoed Voice|Echoed Voice]]'
- - Beginner
  - '[[SRD-Rock Smash|Rock Smash]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Supersonic|Supersonic]]'
- - Amateur
  - '[[SRD-Pluck|Pluck]]'
- - Amateur
  - '[[SRD-Roost|Roost]]'
- - Amateur
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Drill Peck|Drill Peck]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Bullet Seed|Bullet Seed]]'
- - Ace
  - '[[SRD-Feather Dance|Feather Dance]]'
- - Ace
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Uproar|Uproar]]'
- - Pro
  - '[[SRD-Tailwind|Tailwind]]'
- - Pro
  - '[[SRD-Mirror Move|Mirror Move]]'
Name: Pikipek
Species: '[[SRD-Pikipek|Pikipek]]'
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
