---
DexID: '0124'
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Lick|Lick]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Lovely Kiss|Lovely Kiss]]'
- - Beginner
  - '[[SRD-Powder Snow|Powder Snow]]'
- - Beginner
  - '[[SRD-Draining Kiss|Draining Kiss]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - Amateur
  - '[[SRD-Double Slap|Double Slap]]'
- - Amateur
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Amateur
  - '[[SRD-Heart Stamp|Heart Stamp]]'
- - Amateur
  - '[[SRD-Mean Look|Mean Look]]'
- - Amateur
  - '[[SRD-Fake Tears|Fake Tears]]'
- - Amateur
  - '[[SRD-Wake-Up Slap|Wake-Up Slap]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Avalanche|Avalanche]]'
- - Ace
  - '[[SRD-Perish Song|Perish Song]]'
- - Ace
  - '[[SRD-Wring Out|Wring Out]]'
- - Ace
  - '[[SRD-Blizzard|Blizzard]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Fake Out|Fake Out]]'
- - Pro
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Pro
  - '[[SRD-Aurora Veil|Aurora Veil]]'
Name: Jynx
Species: '[[SRD-Jynx|Jynx]]'
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
