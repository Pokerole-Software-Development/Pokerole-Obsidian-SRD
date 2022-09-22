---
DexID: 0842
Moves:
- - Starter
  - '[[SRD-Wrap|Wrap]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Minimize|Minimize]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Brutal Swing|Brutal Swing]]'
- - Amateur
  - '[[SRD-Bulldoze|Bulldoze]]'
- - Amateur
  - '[[SRD-Slam|Slam]]'
- - Amateur
  - '[[SRD-Glare|Glare]]'
- - Amateur
  - '[[SRD-Dig|Dig]]'
- - Amateur
  - '[[SRD-Sandstorm|Sandstorm]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Headbutt|Headbutt]]'
- - Ace
  - '[[SRD-Coil|Coil]]'
- - Ace
  - '[[SRD-Sand Tomb|Sand Tomb]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Pro
  - '[[SRD-Poison Tail|Poison Tail]]'
- - Pro
  - '[[SRD-Last Resort|Last Resort]]'
Name: Silicobra
Species: '[[SRD-Silicobra|Silicobra]]'
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
