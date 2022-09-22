---
DexID: '0275'
Moves:
- - Starter
  - '[[SRD-Feint Attack|Feint Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Amateur
  - '[[SRD-Whirlwind|Whirlwind]]'
- - Amateur
  - '[[SRD-Leaf Tornado|Leaf Tornado]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hurricane|Hurricane]]'
- - Ace
  - '[[SRD-Leaf Storm|Leaf Storm]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Seed Bomb|Seed Bomb]]'
- - Pro
  - '[[SRD-Self Destruct|Self Destruct]]'
- - Pro
  - '[[SRD-Sucker Punch|Sucker Punch]]'
Name: Shiftry
Species: '[[SRD-Shiftry|Shiftry]]'
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
