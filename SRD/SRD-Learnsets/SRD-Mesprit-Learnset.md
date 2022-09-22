---
DexID: 0481
Moves:
- - Master
  - '[[SRD-Healing Wish|Healing Wish]]'
- - Master
  - '[[SRD-Natural Gift|Natural Gift]]'
- - Master
  - '[[SRD-Copycat|Copycat]]'
- - Master
  - '[[SRD-Rest|Rest]]'
- - Master
  - '[[SRD-Confusion|Confusion]]'
- - Master
  - '[[SRD-Imprison|Imprison]]'
- - Master
  - '[[SRD-Protect|Protect]]'
- - Master
  - '[[SRD-Swift|Swift]]'
- - Master
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - Master
  - '[[SRD-Future Sight|Future Sight]]'
- - Master
  - '[[SRD-Charm|Charm]]'
- - Master
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Master
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Master
  - '[[SRD-Hidden Power|Hidden Power]]'
- - Master
  - '[[SRD-Psych Up|Psych Up]]'
- - Master
  - '[[SRD-Role Play|Role Play]]'
- - Master
  - '[[SRD-Knock Off|Knock Off]]'
- - Master
  - '[[SRD-Trick|Trick]]'
Name: Mesprit
Species: '[[SRD-Mesprit|Mesprit]]'
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
