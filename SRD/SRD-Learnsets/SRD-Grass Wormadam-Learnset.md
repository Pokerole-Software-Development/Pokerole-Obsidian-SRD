---
DexID: '0413'
Moves:
- - Starter
  - '[[SRD-Protect|Protect]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Captivate|Captivate]]'
- - Amateur
  - '[[SRD-Flail|Flail]]'
- - Amateur
  - '[[SRD-Bug Bite|Bug Bite]]'
- - Amateur
  - '[[SRD-Hidden Power|Hidden Power]]'
- - Amateur
  - '[[SRD-Confusion|Confusion]]'
- - Amateur
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Amateur
  - '[[SRD-Growth|Growth]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Quiver Dance|Quiver Dance]]'
- - Ace
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Ace
  - '[[SRD-Attract|Attract]]'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Leaf Storm|Leaf Storm]]'
- - Ace
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Synthesis|Synthesis]]'
- - Pro
  - '[[SRD-Electroweb|Electroweb]]'
- - Pro
  - '[[SRD-Giga Drain|Giga Drain]]'
Name: Grass Wormadam
Species: '[[SRD-Grass Wormadam|Grass Wormadam]]'
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
