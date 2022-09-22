---
DexID: '0630'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - Starter
  - '[[SRD-Lick|Lick]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Incinerate|Incinerate]]'
- - Beginner
  - '[[SRD-Hone Claws|Hone Claws]]'
- - Beginner
  - '[[SRD-Bind|Bind]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fire Spin|Fire Spin]]'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Snatch|Snatch]]'
- - Amateur
  - '[[SRD-Flame Burst|Flame Burst]]'
- - Amateur
  - '[[SRD-Bug Bite|Bug Bite]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Amnesia|Amnesia]]'
- - Amateur
  - '[[SRD-Fire Lash|Fire Lash]]'
- - Amateur
  - '[[SRD-Flamethrower|Flamethrower]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Stockpile|Stockpile]]'
- - Ace
  - '[[SRD-Swallow|Swallow]]'
- - Ace
  - '[[SRD-Spit Up|Spit Up]]'
- - Ace
  - '[[SRD-Inferno|Inferno]]'
- - Ace
  - '[[SRD-Flare Blitz|Flare Blitz]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Pro
  - '[[SRD-Fire Punch|Fire Punch]]'
- - Pro
  - '[[SRD-Night Slash|Night Slash]]'
Name: Heatmor
Species: '[[SRD-Heatmor|Heatmor]]'
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
