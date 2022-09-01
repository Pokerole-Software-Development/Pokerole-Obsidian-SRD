---
DexID: '0036'
Moves:
- - Beginner
  - '[[SRD-Spotlight|Spotlight]]'
- - Beginner
  - '[[SRD-Sing|Sing]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Moonblast|Moonblast]]'
- - Amateur
  - '[[SRD-Minimize|Minimize]]'
- - Amateur
  - '[[SRD-Double Slap|Double Slap]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Drain Punch|Drain Punch]]'
- - Ace
  - '[[SRD-Metronome|Metronome]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - Pro
  - '[[SRD-Wish|Wish]]'
Name: Clefable
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
