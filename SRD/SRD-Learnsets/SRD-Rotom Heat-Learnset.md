---
DexID: 0479F1
Moves:
- - Starter
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Beginner
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - Beginner
  - '[[SRD-Uproar|Uproar]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Trick|Trick]]'
- - Amateur
  - '[[SRD-Double Team|Double Team]]'
- - Amateur
  - '[[SRD-Shock Wave|Shock Wave]]'
- - Amateur
  - '[[SRD-Ominous Wind|Ominous Wind]]'
- - Amateur
  - '[[SRD-Substitute|Substitute]]'
- - Amateur
  - '[[SRD-Electro Ball|Electro Ball]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hex|Hex]]'
- - Ace
  - '[[SRD-Charge|Charge]]'
- - Ace
  - '[[SRD-Discharge|Discharge]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Overheat|Overheat]]'
Name: Rotom Heat
Species: '[[SRD-Rotom Heat|Rotom Heat]]'
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
