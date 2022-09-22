---
DexID: '0736'
Moves:
- - Starter
  - '[[SRD-String Shot|String Shot]]'
- - Starter
  - '[[SRD-Vice Grip|Vice Grip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Beginner
  - '[[SRD-Bug Bite|Bug Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Charge|Charge]]'
- - Amateur
  - '[[SRD-Spark|Spark]]'
- - Amateur
  - '[[SRD-Acrobatics|Acrobatics]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Dig|Dig]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-X-Scissor|X-Scissor]]'
- - Ace
  - '[[SRD-Discharge|Discharge]]'
- - Ace
  - '[[SRD-Iron Defense|Iron Defense]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Endure|Endure]]'
- - Pro
  - '[[SRD-Charge Beam|Charge Beam]]'
- - Pro
  - '[[SRD-Electroweb|Electroweb]]'
Name: Charjabug
Species: '[[SRD-Charjabug|Charjabug]]'
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
