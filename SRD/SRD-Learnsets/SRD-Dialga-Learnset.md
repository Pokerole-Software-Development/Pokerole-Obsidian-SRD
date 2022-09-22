---
DexID: 0483
Moves:
- - Master
  - '[[SRD-Dragon Breath|Dragon Breath]]'
- - Master
  - '[[SRD-Scary Face|Scary Face]]'
- - Master
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Slash|Slash]]'
- - Master
  - '[[SRD-Power Gem|Power Gem]]'
- - Master
  - '[[SRD-Metal Burst|Metal Burst]]'
- - Master
  - '[[SRD-Dragon Claw|Dragon Claw]]'
- - Master
  - '[[SRD-Earth Power|Earth Power]]'
- - Master
  - '[[SRD-Aura Sphere|Aura Sphere]]'
- - Master
  - '[[SRD-Iron Tail|Iron Tail]]'
- - Master
  - '[[SRD-Roar Of Time|Roar Of Time]]'
- - Master
  - '[[SRD-Flash Cannon|Flash Cannon]]'
- - Master
  - '[[SRD-Hidden Power|Hidden Power]]'
- - Master
  - '[[SRD-Psych Up|Psych Up]]'
- - Master
  - '[[SRD-Trick Room|Trick Room]]'
- - Master
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Master
  - '[[SRD-Iron Defense|Iron Defense]]'
Name: Dialga
Species: '[[SRD-Dialga|Dialga]]'
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
