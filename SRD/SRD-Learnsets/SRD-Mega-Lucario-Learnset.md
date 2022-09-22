---
DexID: 0448M1
Moves:
- - Starter
  - '[[SRD-Laser Focus|Laser Focus]]'
- - Starter
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Starter
  - '[[SRD-Foresight|Foresight]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Beginner
  - '[[SRD-Detect|Detect]]'
- - Beginner
  - '[[SRD-Feint|Feint]]'
- - Beginner
  - '[[SRD-Counter|Counter]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Amateur
  - '[[SRD-Power-Up Punch|Power-Up Punch]]'
- - Amateur
  - '[[SRD-Bone Rush|Bone Rush]]'
- - Amateur
  - '[[SRD-Metal Sound|Metal Sound]]'
- - Amateur
  - '[[SRD-Me First|Me First]]'
- - Amateur
  - '[[SRD-Quick Guard|Quick Guard]]'
- - Amateur
  - '[[SRD-Work Up|Work Up]]'
- - Amateur
  - '[[SRD-Aura Sphere|Aura Sphere]]'
- - Amateur
  - '[[SRD-Calm Mind|Calm Mind]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - Ace
  - '[[SRD-Close Combat|Close Combat]]'
- - Ace
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Extreme Speed|Extreme Speed]]'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[SRD-Vacuum Wave|Vacuum Wave]]'
Name: Mega-Lucario
Species: '[[SRD-Mega-Lucario|Mega-Lucario]]'
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
