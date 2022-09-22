---
DexID: '0102'
Moves:
- - Starter
  - '[[SRD-Barrage|Barrage]]'
- - Starter
  - '[[SRD-Uproar|Uproar]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Beginner
  - '[[SRD-Reflect|Reflect]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Amateur
  - '[[SRD-Bullet Seed|Bullet Seed]]'
- - Amateur
  - '[[SRD-Stun Spore|Stun Spore]]'
- - Amateur
  - '[[SRD-Poison Powder|Poison Powder]]'
- - Amateur
  - '[[SRD-Sleep Powder|Sleep Powder]]'
- - Amateur
  - '[[SRD-Confusion|Confusion]]'
- - Amateur
  - '[[SRD-Worry Seed|Worry Seed]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Natural Gift|Natural Gift]]'
- - Ace
  - '[[SRD-Solar Beam|Solar Beam]]'
- - Ace
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Ace
  - '[[SRD-Bestow|Bestow]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Nightmare|Nightmare]]'
- - Pro
  - '[[SRD-Ingrain|Ingrain]]'
- - Pro
  - '[[SRD-Curse|Curse]]'
Name: Exeggcute
Species: '[[SRD-Exeggcute|Exeggcute]]'
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
