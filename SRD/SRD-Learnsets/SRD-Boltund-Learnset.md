---
DexID: 0837
Moves:
- - Starter
  - '[[SRD-Electrify|Electrify]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[SRD-Nuzzle|Nuzzle]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Roar|Roar]]'
- - Amateur
  - '[[SRD-Spark|Spark]]'
- - Amateur
  - '[[SRD-Charm|Charm]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Charge|Charge]]'
- - Ace
  - '[[SRD-Wild Charge|Wild Charge]]'
- - Ace
  - '[[SRD-Play Rough|Play Rough]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Electric Terrain|Electric Terrain]]'
- - Pro
  - '[[SRD-Psychic Fangs|Psychic Fangs]]'
- - Pro
  - '[[SRD-Dig|Dig]]'
- - Pro
  - '[[SRD-Thunder Fang|Thunder Fang]]'
Name: Boltund
Species: '[[SRD-Boltund|Boltund]]'
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
