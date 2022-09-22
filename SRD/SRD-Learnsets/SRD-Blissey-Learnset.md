---
DexID: '0242'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Pound|Pound]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Beginner
  - '[[SRD-Double Slap|Double Slap]]'
- - Beginner
  - '[[SRD-Refresh|Refresh]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bestow|Bestow]]'
- - Amateur
  - '[[SRD-Soft Boiled|Soft Boiled]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Minimize|Minimize]]'
- - Amateur
  - '[[SRD-Fling|Fling]]'
- - Amateur
  - '[[SRD-Sing|Sing]]'
- - Amateur
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - '---------------------------'
  - '---------------------------'
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
  - '[[SRD-Seismic Toss|Seismic Toss]]'
- - Pro
  - '[[SRD-Last Resort|Last Resort]]'
- - Pro
  - '[[SRD-Metronome|Metronome]]'
Name: Blissey
Species: '[[SRD-Blissey|Blissey]]'
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
