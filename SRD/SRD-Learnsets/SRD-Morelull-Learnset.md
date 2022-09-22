---
DexID: '0754'
Moves:
- - Starter
  - '[[SRD-Absorb|Absorb]]'
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - Starter
  - '[[SRD-Flash|Flash]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Moonlight|Moonlight]]'
- - Beginner
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Beginner
  - '[[SRD-Sleep Powder|Sleep Powder]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Ingrain|Ingrain]]'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Amateur
  - '[[SRD-Strength Sap|Strength Sap]]'
- - Amateur
  - '[[SRD-Dream Eater|Dream Eater]]'
- - Amateur
  - '[[SRD-Spotlight|Spotlight]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Spore|Spore]]'
- - Ace
  - '[[SRD-Moonblast|Moonblast]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Pro
  - '[[SRD-Amnesia|Amnesia]]'
- - Pro
  - '[[SRD-Light Screen|Light Screen]]'
Name: Morelull
Species: '[[SRD-Morelull|Morelull]]'
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
