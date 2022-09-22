---
DexID: 0801
Moves:
- - Master
  - '[[SRD-Moonlight|Moonlight]]'
- - Master
  - '[[SRD-Morning Sun|Morning Sun]]'
- - Master
  - '[[SRD-Charge Beam|Charge Beam]]'
- - Master
  - '[[SRD-Mirror Shot|Mirror Shot]]'
- - Master
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Master
  - '[[SRD-Confusion|Confusion]]'
- - Master
  - '[[SRD-Slash|Slash]]'
- - Master
  - '[[SRD-Stored Power|Stored Power]]'
- - Master
  - '[[SRD-Rock Blast|Rock Blast]]'
- - Master
  - '[[SRD-Night Slash|Night Slash]]'
- - Master
  - '[[SRD-Gravity|Gravity]]'
- - Master
  - '[[SRD-Psycho Cut|Psycho Cut]]'
- - Master
  - '[[SRD-Power Gem|Power Gem]]'
- - Master
  - '[[SRD-Autotomize|Autotomize]]'
- - Master
  - '[[SRD-Photon Geyser (Special)|Photon Geyser (Special)]]'
- - Master
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Master
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Master
  - '[[SRD-Wring Out|Wring Out]]'
- - Master
  - '[[SRD-Prismatic Laser|Prismatic Laser]]'
- - Master
  - '[[SRD-Outrage|Outrage]]'
- - Master
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Master
  - '[[SRD-Sunsteel Strike|Sunsteel Strike]]'
- - Master
  - '[[SRD-Moongeist Beam|Moongeist Beam]]'
Name: Necrozma Ultra Burst
Species: '[[SRD-Necrozma Ultra Burst|Necrozma Ultra Burst]]'
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
