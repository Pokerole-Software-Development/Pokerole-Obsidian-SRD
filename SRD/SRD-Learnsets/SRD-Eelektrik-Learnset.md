---
DexID: '0604'
Moves:
- - Starter
  - '[[SRD-Spark|Spark]]'
- - Starter
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bind|Bind]]'
- - Beginner
  - '[[SRD-Charge Beam|Charge Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Acid|Acid]]'
- - Amateur
  - '[[SRD-Discharge|Discharge]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Thunderbolt|Thunderbolt]]'
- - Amateur
  - '[[SRD-Acid Spray|Acid Spray]]'
- - Amateur
  - '[[SRD-Coil|Coil]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Wild Charge|Wild Charge]]'
- - Ace
  - '[[SRD-Gastro Acid|Gastro Acid]]'
- - Ace
  - '[[SRD-Zap Cannon|Zap Cannon]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Pro
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Pro
  - '[[SRD-Iron Tail|Iron Tail]]'
Name: Eelektrik
Species: '[[SRD-Eelektrik|Eelektrik]]'
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
