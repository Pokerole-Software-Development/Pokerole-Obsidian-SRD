---
DexID: '0715'
Moves:
- - Master
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - Master
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - Master
  - '[[SRD-Ingrain|Ingrain]]'
- - Master
  - '[[SRD-Take Down|Take Down]]'
- - Master
  - '[[SRD-Light Screen|Light Screen]]'
- - Master
  - '[[SRD-Aurora Beam|Aurora Beam]]'
- - Master
  - '[[SRD-Gravity|Gravity]]'
- - Master
  - '[[SRD-Geomancy|Geomancy]]'
- - Master
  - '[[SRD-Moonblast|Moonblast]]'
- - Master
  - '[[SRD-Megahorn|Megahorn]]'
- - Master
  - '[[SRD-Night Slash|Night Slash]]'
- - Master
  - '[[SRD-Horn Leech|Horn Leech]]'
- - Master
  - '[[SRD-Psych Up|Psych Up]]'
- - Master
  - '[[SRD-Misty Terrain|Misty Terrain]]'
- - Master
  - '[[SRD-Nature Power|Nature Power]]'
- - Master
  - '[[SRD-Close Combat|Close Combat]]'
- - Master
  - '[[SRD-Giga Impact|Giga Impact]]'
- - Master
  - '[[SRD-Outrage|Outrage]]'
- - Master
  - '[[SRD-Psyshock|Psyshock]]'
- - Master
  - '[[SRD-Thunder|Thunder]]'
- - Master
  - '[[SRD-Reflect|Reflect]]'
- - Master
  - '[[SRD-Endeavor|Endeavor]]'
Name: Xerneas
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
