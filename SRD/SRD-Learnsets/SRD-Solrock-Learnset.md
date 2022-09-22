---
DexID: 0338
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Harden|Harden]]'
- - Starter
  - '[[SRD-Solar Beam|Solar Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Fire Spin|Fire Spin]]'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - Beginner
  - '[[SRD-Rock Throw|Rock Throw]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Rock Polish|Rock Polish]]'
- - Amateur
  - '[[SRD-Psywave|Psywave]]'
- - Amateur
  - '[[SRD-Embargo|Embargo]]'
- - Amateur
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Amateur
  - '[[SRD-Cosmic Power|Cosmic Power]]'
- - Amateur
  - '[[SRD-Psychic|Psychic]]'
- - Amateur
  - '[[SRD-Heal Block|Heal Block]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Stone Edge|Stone Edge]]'
- - Ace
  - '[[SRD-Explosion|Explosion]]'
- - Ace
  - '[[SRD-Flare Blitz|Flare Blitz]]'
- - Ace
  - '[[SRD-Wonder Room|Wonder Room]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Magic Coat|Magic Coat]]'
- - Pro
  - '[[SRD-Sunny Day|Sunny Day]]'
- - Pro
  - '[[SRD-Skill Swap|Skill Swap]]'
Name: Solrock
Species: '[[SRD-Solrock|Solrock]]'
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
