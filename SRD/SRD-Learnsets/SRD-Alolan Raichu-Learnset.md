---
DexID: 0026A
Moves:
- - Starter
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Amateur
  - '[[SRD-Thunderbolt|Thunderbolt]]'
- - Amateur
  - '[[SRD-Psychic|Psychic]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Speed Swap|Speed Swap]]'
- - Ace
  - '[[SRD-Electric Terrain|Electric Terrain]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Reflect|Reflect]]'
- - Pro
  - '[[SRD-Volt Tackle|Volt Tackle]]'
Name: Alolan Raichu
Species: '[[SRD-Alolan Raichu|Alolan Raichu]]'
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
