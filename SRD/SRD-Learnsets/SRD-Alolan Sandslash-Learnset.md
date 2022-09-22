---
DexID: 0028A
Moves:
- - Starter
  - '[[SRD-Icicle Spear|Icicle Spear]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Metal Burst|Metal Burst]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Icicle Crash|Icicle Crash]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Amateur
  - '[[SRD-Ice Ball|Ice Ball]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Ace
  - '[[SRD-Chip Away|Chip Away]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Counter|Counter]]'
- - Pro
  - '[[SRD-Aurora Veil|Aurora Veil]]'
Name: Alolan Sandslash
Species: '[[SRD-Alolan Sandslash|Alolan Sandslash]]'
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
