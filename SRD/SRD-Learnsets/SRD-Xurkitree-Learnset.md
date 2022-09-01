---
DexID: 0795
Moves:
- - Master
  - '[[SRD-Tail Glow|Tail Glow]]'
- - Master
  - '[[SRD-Spark|Spark]]'
- - Master
  - '[[SRD-Charge|Charge]]'
- - Master
  - '[[SRD-Wrap|Wrap]]'
- - Master
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - Master
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Master
  - '[[SRD-Shock Wave|Shock Wave]]'
- - Master
  - '[[SRD-Ingrain|Ingrain]]'
- - Master
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Master
  - '[[SRD-Eerie Impulse|Eerie Impulse]]'
- - Master
  - '[[SRD-Signal Beam|Signal Beam]]'
- - Master
  - '[[SRD-Thunderbolt|Thunderbolt]]'
- - Master
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Master
  - '[[SRD-Discharge|Discharge]]'
- - Master
  - '[[SRD-Electric Terrain|Electric Terrain]]'
- - Master
  - '[[SRD-Power Whip|Power Whip]]'
- - Master
  - '[[SRD-Ion Deluge|Ion Deluge]]'
- - Master
  - '[[SRD-Zap Cannon|Zap Cannon]]'
- - Master
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Master
  - '[[SRD-Brutal Swing|Brutal Swing]]'
- - Master
  - '[[SRD-Electroweb|Electroweb]]'
Name: Xurkitree
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
