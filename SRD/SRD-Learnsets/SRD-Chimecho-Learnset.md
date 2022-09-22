---
DexID: 0358
Moves:
- - Starter
  - '[[SRD-Wrap|Wrap]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Astonish|Astonish]]'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Uproar|Uproar]]'
- - Amateur
  - '[[SRD-Confusion|Confusion]]'
- - Amateur
  - '[[SRD-Yawn|Yawn]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Safeguard|Safeguard]]'
- - Amateur
  - '[[SRD-Psywave|Psywave]]'
- - Amateur
  - '[[SRD-Healing Wish|Healing Wish]]'
- - Amateur
  - '[[SRD-Heal Bell|Heal Bell]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Ace
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - Ace
  - '[[SRD-Synchronoise|Synchronoise]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Recover|Recover]]'
- - Pro
  - '[[SRD-Cosmic Power|Cosmic Power]]'
- - Pro
  - '[[SRD-Stored Power|Stored Power]]'
Name: Chimecho
Species: '[[SRD-Chimecho|Chimecho]]'
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
