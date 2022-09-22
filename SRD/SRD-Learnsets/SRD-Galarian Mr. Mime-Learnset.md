---
DexID: 0122G
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Beginner
  - '[[SRD-Ice Shard|Ice Shard]]'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - Beginner
  - '[[SRD-Ally Switch|Ally Switch]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Amateur
  - '[[SRD-Double Kick|Double Kick]]'
- - Amateur
  - '[[SRD-Copycat|Copycat]]'
- - Amateur
  - '[[SRD-Encore|Encore]]'
- - Amateur
  - '[[SRD-Role Play|Role Play]]'
- - Amateur
  - '[[SRD-Protect|Protect]]'
- - Amateur
  - '[[SRD-Recycle|Recycle]]'
- - Amateur
  - '[[SRD-Mimic|Mimic]]'
- - Amateur
  - '[[SRD-Light Screen|Light Screen]]'
- - Amateur
  - '[[SRD-Reflect|Reflect]]'
- - Amateur
  - '[[SRD-Ice Beam|Ice Beam]]'
- - Amateur
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Amateur
  - '[[SRD-Mirror Coat|Mirror Coat]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Ace
  - '[[SRD-Freeze Dry|Freeze Dry]]'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Safeguard|Safeguard]]'
- - Ace
  - '[[SRD-Dazzling Gleam|Dazzling Gleam]]'
- - Ace
  - '[[SRD-Misty Terrain|Misty Terrain]]'
- - Ace
  - '[[SRD-Teeter Dance|Teeter Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Pro
  - '[[SRD-Hail|Hail]]'
Name: Galarian Mr. Mime
Species: '[[SRD-Galarian Mr. Mime|Galarian Mr. Mime]]'
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
