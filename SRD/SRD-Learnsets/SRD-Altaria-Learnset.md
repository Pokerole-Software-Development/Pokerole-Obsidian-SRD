---
DexID: '0334'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Peck|Peck]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Pluck|Pluck]]'
- - Beginner
  - '[[SRD-Astonish|Astonish]]'
- - Beginner
  - '[[SRD-Sing|Sing]]'
- - Beginner
  - '[[SRD-Fury Attack|Fury Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Safeguard|Safeguard]]'
- - Amateur
  - '[[SRD-Disarming Voice|Disarming Voice]]'
- - Amateur
  - '[[SRD-Mist|Mist]]'
- - Amateur
  - '[[SRD-Round|Round]]'
- - Amateur
  - '[[SRD-Natural Gift|Natural Gift]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Refresh|Refresh]]'
- - Amateur
  - '[[SRD-Dragon Dance|Dragon Dance]]'
- - Amateur
  - '[[SRD-Dragon Breath|Dragon Breath]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Cotton Guard|Cotton Guard]]'
- - Ace
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Ace
  - '[[SRD-Perish Song|Perish Song]]'
- - Ace
  - '[[SRD-Moonblast|Moonblast]]'
- - Ace
  - '[[SRD-Sky Attack|Sky Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Power Swap|Power Swap]]'
- - Pro
  - '[[SRD-Draco Meteor|Draco Meteor]]'
- - Pro
  - '[[SRD-Dragon Rush|Dragon Rush]]'
Name: Altaria
Species: '[[SRD-Altaria|Altaria]]'
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
