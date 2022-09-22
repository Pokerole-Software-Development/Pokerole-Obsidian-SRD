---
DexID: 0289
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Yawn|Yawn]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Encore|Encore]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Punishment|Punishment]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Slack Off|Slack Off]]'
- - Amateur
  - '[[SRD-Covet|Covet]]'
- - Amateur
  - '[[SRD-Encore|Encore]]'
- - Amateur
  - '[[SRD-Fling|Fling]]'
- - Amateur
  - '[[SRD-Amnesia|Amnesia]]'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Ace
  - '[[SRD-Chip Away|Chip Away]]'
- - Ace
  - '[[SRD-Counter|Counter]]'
- - Ace
  - '[[SRD-Flail|Flail]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Block|Block]]'
- - Pro
  - '[[SRD-Focus Punch|Focus Punch]]'
- - Pro
  - '[[SRD-Gunk Shot|Gunk Shot]]'
Name: Slaking
Species: '[[SRD-Slaking|Slaking]]'
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
