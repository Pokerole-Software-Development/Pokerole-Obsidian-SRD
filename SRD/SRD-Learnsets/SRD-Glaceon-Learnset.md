---
DexID: '0471'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Starter
  - '[[SRD-Helping Hand|Helping Hand]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Icy Wind|Icy Wind]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Amateur
  - '[[SRD-Ice Shard|Ice Shard]]'
- - Amateur
  - '[[SRD-Barrier|Barrier]]'
- - Amateur
  - '[[SRD-Mirror Coat|Mirror Coat]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hail|Hail]]'
- - Ace
  - '[[SRD-Last Resort|Last Resort]]'
- - Ace
  - '[[SRD-Blizzard|Blizzard]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Wish|Wish]]'
- - Pro
  - '[[SRD-Captivate|Captivate]]'
- - Pro
  - '[[SRD-Fake Tears|Fake Tears]]'
Name: Glaceon
Species: '[[SRD-Glaceon|Glaceon]]'
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
