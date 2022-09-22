---
DexID: '0026'
Moves:
- - Starter
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Thunderbolt|Thunderbolt]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Fake Out|Fake Out]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Wish|Wish]]'
- - Pro
  - '[[SRD-Volt Tackle|Volt Tackle]]'
Name: Raichu
Species: '[[SRD-Raichu|Raichu]]'
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
