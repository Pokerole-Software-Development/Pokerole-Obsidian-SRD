---
DexID: 0749
Moves:
- - Starter
  - '[[SRD-Peck|Peck]]'
- - Starter
  - '[[SRD-Poison Sting|Poison Sting]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Toxic Spikes|Toxic Spikes]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Wide Guard|Wide Guard]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Baneful Bunker|Baneful Bunker]]'
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
  - '[[SRD-Swallow|Swallow]]'
- - Pro
  - '[[SRD-Stockpile|Stockpile]]'
- - Pro
  - '[[SRD-Spit Up|Spit Up]]'
Name: Toxapex
Species: '[[SRD-Toxapex|Toxapex]]'
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
