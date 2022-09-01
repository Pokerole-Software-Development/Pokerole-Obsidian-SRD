---
DexID: 0805
Moves:
- - Master
  - '[[SRD-Air Cutter|Air Cutter]]'
- - Master
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Master
  - '[[SRD-Peck|Peck]]'
- - Master
  - '[[SRD-Growl|Growl]]'
- - Master
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Master
  - '[[SRD-Acid|Acid]]'
- - Master
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Master
  - '[[SRD-Venoshock|Venoshock]]'
- - Master
  - '[[SRD-Charm|Charm]]'
- - Master
  - '[[SRD-Venom Drench|Venom Drench]]'
- - Master
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Master
  - '[[SRD-Poison Jab|Poison Jab]]'
- - Master
  - '[[SRD-Toxic|Toxic]]'
- - Master
  - '[[SRD-Fell Stinger|Fell Stinger]]'
- - Master
  - '[[SRD-Air Slash|Air Slash]]'
- - Master
  - '[[SRD-Draco Meteor|Draco Meteor]]'
- - Master
  - '[[SRD-Gunk Shot|Gunk Shot]]'
- - Master
  - '[[SRD-Tailwind|Tailwind]]'
- - Master
  - '[[SRD-Sky Attack|Sky Attack]]'
Name: Naganadel
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
