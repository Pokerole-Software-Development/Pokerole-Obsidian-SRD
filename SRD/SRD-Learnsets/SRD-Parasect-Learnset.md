---
DexID: '0047'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Stun Spore|Stun Spore]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Absorb|Absorb]]'
- - Beginner
  - '[[SRD-Poison Powder|Poison Powder]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Cross Poison|Cross Poison]]'
- - Amateur
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - Amateur
  - '[[SRD-Spore|Spore]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Growth|Growth]]'
- - Amateur
  - '[[SRD-Giga Drain|Giga Drain]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - Ace
  - '[[SRD-Rage Powder|Rage Powder]]'
- - Ace
  - '[[SRD-X-Scissor|X-Scissor]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Psybeam|Psybeam]]'
- - Pro
  - '[[SRD-Synthesis|Synthesis]]'
- - Pro
  - '[[SRD-Seed Bomb|Seed Bomb]]'
Name: Parasect
Species: '[[SRD-Parasect|Parasect]]'
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
