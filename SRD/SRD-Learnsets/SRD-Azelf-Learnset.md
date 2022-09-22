---
DexID: 0482
Moves:
- - Master
  - '[[SRD-Last Resort|Last Resort]]'
- - Master
  - '[[SRD-Natural Gift|Natural Gift]]'
- - Master
  - '[[SRD-Flail|Flail]]'
- - Master
  - '[[SRD-Rest|Rest]]'
- - Master
  - '[[SRD-Confusion|Confusion]]'
- - Master
  - '[[SRD-Imprison|Imprison]]'
- - Master
  - '[[SRD-Detect|Detect]]'
- - Master
  - '[[SRD-Swift|Swift]]'
- - Master
  - '[[SRD-Uproar|Uproar]]'
- - Master
  - '[[SRD-Future Sight|Future Sight]]'
- - Master
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Master
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Master
  - '[[SRD-Explosion|Explosion]]'
- - Master
  - '[[SRD-Hidden Power|Hidden Power]]'
- - Master
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Master
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Master
  - '[[SRD-Skill Swap|Skill Swap]]'
- - Master
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
Name: Azelf
Species: '[[SRD-Azelf|Azelf]]'
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
