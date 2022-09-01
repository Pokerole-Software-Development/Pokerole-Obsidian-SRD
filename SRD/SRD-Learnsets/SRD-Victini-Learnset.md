---
DexID: 0494
Moves:
- - Master
  - '[[SRD-Searing Shot|Searing Shot]]'
- - Master
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Master
  - '[[SRD-Confusion|Confusion]]'
- - Master
  - '[[SRD-Incinerate|Incinerate]]'
- - Master
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Master
  - '[[SRD-Endure|Endure]]'
- - Master
  - '[[SRD-Headbutt|Headbutt]]'
- - Master
  - '[[SRD-Flame Charge|Flame Charge]]'
- - Master
  - '[[SRD-Reversal|Reversal]]'
- - Master
  - '[[SRD-Flame Burst|Flame Burst]]'
- - Master
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Master
  - '[[SRD-Inferno|Inferno]]'
- - Master
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Master
  - '[[SRD-Flare Blitz|Flare Blitz]]'
- - Master
  - '[[SRD-Final Gambit|Final Gambit]]'
- - Master
  - '[[SRD-Stored Power|Stored Power]]'
- - Master
  - '[[SRD-Overheat|Overheat]]'
- - Master
  - '[[SRD-Trick|Trick]]'
- - Master
  - '[[SRD-Shock Wave|Shock Wave]]'
- - Master
  - '[[SRD-V-Create|V-Create]]'
Name: Victini
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
