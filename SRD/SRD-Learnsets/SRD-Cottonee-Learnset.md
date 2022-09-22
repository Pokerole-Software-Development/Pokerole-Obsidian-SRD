---
DexID: '0546'
Moves:
- - Starter
  - '[[SRD-Absorb|Absorb]]'
- - Starter
  - '[[SRD-Fairy Wind|Fairy Wind]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Growth|Growth]]'
- - Beginner
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Beginner
  - '[[SRD-Stun Spore|Stun Spore]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Amateur
  - '[[SRD-Cotton Spore|Cotton Spore]]'
- - Amateur
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Amateur
  - '[[SRD-Poison Powder|Poison Powder]]'
- - Amateur
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Amateur
  - '[[SRD-Charm|Charm]]'
- - Amateur
  - '[[SRD-Energy Ball|Energy Ball]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Ace
  - '[[SRD-Cotton Guard|Cotton Guard]]'
- - Ace
  - '[[SRD-Sunny Day|Sunny Day]]'
- - Ace
  - '[[SRD-Endeavor|Endeavor]]'
- - Ace
  - '[[SRD-Solar Beam|Solar Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Beat Up|Beat Up]]'
- - Pro
  - '[[SRD-Fake Tears|Fake Tears]]'
- - Pro
  - '[[SRD-Encore|Encore]]'
Name: Cottonee
Species: '[[SRD-Cottonee|Cottonee]]'
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
