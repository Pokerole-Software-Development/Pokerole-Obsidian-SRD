---
DexID: 0584
Moves:
- - Starter
  - '[[SRD-Harden|Harden]]'
- - Starter
  - '[[SRD-Icicle Spear|Icicle Spear]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Uproar|Uproar]]'
- - Beginner
  - '[[SRD-Astonish|Astonish]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Freeze Dry|Freeze Dry]]'
- - Amateur
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Amateur
  - '[[SRD-Mist|Mist]]'
- - Amateur
  - '[[SRD-Avalanche|Avalanche]]'
- - Amateur
  - '[[SRD-Taunt|Taunt]]'
- - Amateur
  - '[[SRD-Mirror Shot|Mirror Shot]]'
- - Amateur
  - '[[SRD-Acid Armor|Acid Armor]]'
- - Amateur
  - '[[SRD-Ice Beam|Ice Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hail|Hail]]'
- - Ace
  - '[[SRD-Mirror Coat|Mirror Coat]]'
- - Ace
  - '[[SRD-Blizzard|Blizzard]]'
- - Ace
  - '[[SRD-Sheer Cold|Sheer Cold]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Autotomize|Autotomize]]'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[SRD-Ice Shard|Ice Shard]]'
Name: Vanilluxe
Species: '[[SRD-Vanilluxe|Vanilluxe]]'
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
