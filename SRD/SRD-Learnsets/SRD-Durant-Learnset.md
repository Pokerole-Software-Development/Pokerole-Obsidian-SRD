---
DexID: '0633'
Moves:
- - Starter
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Starter
  - '[[SRD-Vice Grip|Vice Grip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Metal Sound|Metal Sound]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Amateur
  - '[[SRD-Bug Bite|Bug Bite]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Iron Head|Iron Head]]'
- - Amateur
  - '[[SRD-Dig|Dig]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Entrainment|Entrainment]]'
- - Ace
  - '[[SRD-X-Scissor|X-Scissor]]'
- - Ace
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Ace
  - '[[SRD-Guillotine|Guillotine]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Screech|Screech]]'
- - Pro
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Pro
  - '[[SRD-Superpower|Superpower]]'
Name: Durant
Species: '[[SRD-Durant|Durant]]'
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
