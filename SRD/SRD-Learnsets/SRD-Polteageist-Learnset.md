---
DexID: 0856
Moves:
- - Starter
  - '[[SRD-Teatime|Teatime]]'
- - Starter
  - '[[SRD-Withdraw|Withdraw]]'
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Beginner
  - '[[SRD-Aromatic Mist|Aromatic Mist]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Amateur
  - '[[SRD-Protect|Protect]]'
- - Amateur
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Amateur
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Ace
  - '[[SRD-Shell Smash|Shell Smash]]'
- - Ace
  - '[[SRD-Memento|Memento]]'
- - Ace
  - '[[SRD-Strength Sap|Strength Sap]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Poltergeist|Poltergeist]]'
- - Pro
  - '[[SRD-Stored Power|Stored Power]]'
- - Pro
  - '[[SRD-Self Destruct|Self Destruct]]'
Name: Polteageist
Species: '[[SRD-Polteageist|Polteageist]]'
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
