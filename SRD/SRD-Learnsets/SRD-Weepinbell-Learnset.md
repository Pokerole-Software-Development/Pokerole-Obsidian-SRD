---
DexID: '0070'
Moves:
- - Starter
  - '[[SRD-Vine Whip|Vine Whip]]'
- - Starter
  - '[[SRD-Growth|Growth]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Wrap|Wrap]]'
- - Beginner
  - '[[SRD-Sleep Powder|Sleep Powder]]'
- - Beginner
  - '[[SRD-Poison Powder|Poison Powder]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Stun Spore|Stun Spore]]'
- - Amateur
  - '[[SRD-Acid|Acid]]'
- - Amateur
  - '[[SRD-Knock Off|Knock Off]]'
- - Amateur
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Amateur
  - '[[SRD-Gastro Acid|Gastro Acid]]'
- - Amateur
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Slam|Slam]]'
- - Ace
  - '[[SRD-Poison Jab|Poison Jab]]'
- - Ace
  - '[[SRD-Wring Out|Wring Out]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Ingrain|Ingrain]]'
- - Pro
  - '[[SRD-Tickle|Tickle]]'
- - Pro
  - '[[SRD-Weather Ball|Weather Ball]]'
Name: Weepinbell
Species: '[[SRD-Weepinbell|Weepinbell]]'
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
