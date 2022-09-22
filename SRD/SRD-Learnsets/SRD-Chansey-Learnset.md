---
DexID: '0113'
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Defense Curl|Defense Curl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Refresh|Refresh]]'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - Beginner
  - '[[SRD-Soft Boiled|Soft Boiled]]'
- - Beginner
  - '[[SRD-Double Slap|Double Slap]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - Amateur
  - '[[SRD-Bestow|Bestow]]'
- - Amateur
  - '[[SRD-Minimize|Minimize]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Sing|Sing]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Fling|Fling]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Egg Bomb|Egg Bomb]]'
- - Ace
  - '[[SRD-Light Screen|Light Screen]]'
- - Ace
  - '[[SRD-Healing Wish|Healing Wish]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Heal Bell|Heal Bell]]'
- - Pro
  - '[[SRD-Seismic Toss|Seismic Toss]]'
- - Pro
  - '[[SRD-Present|Present]]'
Name: Chansey
Species: '[[SRD-Chansey|Chansey]]'
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
