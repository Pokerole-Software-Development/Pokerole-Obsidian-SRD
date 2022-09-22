---
DexID: 0269
Moves:
- - Starter
  - '[[SRD-Confusion|Confusion]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Gust|Gust]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Protect|Protect]]'
- - Amateur
  - '[[SRD-Moonlight|Moonlight]]'
- - Amateur
  - '[[SRD-Venoshock|Venoshock]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Whirlwind|Whirlwind]]'
- - Amateur
  - '[[SRD-Light Screen|Light Screen]]'
- - Amateur
  - '[[SRD-Silver Wind|Silver Wind]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Toxic|Toxic]]'
- - Ace
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - Ace
  - '[[SRD-Quiver Dance|Quiver Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Air Cutter|Air Cutter]]'
- - Pro
  - '[[SRD-Swift|Swift]]'
- - Pro
  - '[[SRD-Twister|Twister]]'
Name: Dustox
Species: '[[SRD-Dustox|Dustox]]'
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
