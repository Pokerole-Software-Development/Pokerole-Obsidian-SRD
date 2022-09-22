---
DexID: '0474'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Conversion|Conversion]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Conversion 2|Conversion 2]]'
- - Beginner
  - '[[SRD-Psybeam|Psybeam]]'
- - Beginner
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Trick Room|Trick Room]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Recover|Recover]]'
- - Amateur
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Amateur
  - '[[SRD-Signal Beam|Signal Beam]]'
- - Amateur
  - '[[SRD-Embargo|Embargo]]'
- - Amateur
  - '[[SRD-Discharge|Discharge]]'
- - Amateur
  - '[[SRD-Lock-On|Lock-On]]'
- - Amateur
  - '[[SRD-Tri Attack|Tri Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Magic Coat|Magic Coat]]'
- - Ace
  - '[[SRD-Zap Cannon|Zap Cannon]]'
- - Ace
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Electroweb|Electroweb]]'
- - Pro
  - '[[SRD-Pain Split|Pain Split]]'
- - Pro
  - '[[SRD-Trick|Trick]]'
Name: Porygon-Z
Species: '[[SRD-Porygon-Z|Porygon-Z]]'
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
