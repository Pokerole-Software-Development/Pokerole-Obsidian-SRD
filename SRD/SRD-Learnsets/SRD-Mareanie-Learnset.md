---
DexID: 0746F1
Moves:
- - Starter
  - '[[SRD-Poison Sting|Poison Sting]]'
- - Starter
  - '[[SRD-Peck|Peck]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Toxic Spikes|Toxic Spikes]]'
- - Beginner
  - '[[SRD-Wide Guard|Wide Guard]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Toxic|Toxic]]'
- - Amateur
  - '[[SRD-Venoshock|Venoshock]]'
- - Amateur
  - '[[SRD-Spike Cannon|Spike Cannon]]'
- - Amateur
  - '[[SRD-Pin Missile|Pin Missile]]'
- - Amateur
  - '[[SRD-Poison Jab|Poison Jab]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Venom Drench|Venom Drench]]'
- - Ace
  - '[[SRD-Recover|Recover]]'
- - Ace
  - '[[SRD-Liquidation|Liquidation]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Protect|Protect]]'
- - Pro
  - '[[SRD-Stockpile|Stockpile]]'
- - Pro
  - '[[SRD-Sludge Bomb|Sludge Bomb]]'
Name: Mareanie
Species: '[[SRD-Mareanie|Mareanie]]'
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
