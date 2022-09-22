---
DexID: 0843
Moves:
- - Starter
  - '[[SRD-Withdraw|Withdraw]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Astonish|Astonish]]'
- - Beginner
  - '[[SRD-Headbutt|Headbutt]]'
- - Beginner
  - '[[SRD-Recycle|Recycle]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Growth|Growth]]'
- - Amateur
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - Amateur
  - '[[SRD-Stomp|Stomp]]'
- - Amateur
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Amateur
  - '[[SRD-Protect|Protect]]'
- - Amateur
  - '[[SRD-Bullet Seed|Bullet Seed]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Recover|Recover]]'
- - Ace
  - '[[SRD-Apple Acid|Apple Acid]]'
- - Ace
  - '[[SRD-Body Slam|Body Slam]]'
- - Ace
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Ace
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Ace
  - '[[SRD-Energy Ball|Energy Ball]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Pro
  - '[[SRD-Solar Beam|Solar Beam]]'
- - Pro
  - '[[SRD-Draco Meteor|Draco Meteor]]'
Name: Appletun
Species: '[[SRD-Appletun|Appletun]]'
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
