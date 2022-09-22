---
DexID: 0146G
Moves:
- - Master
  - '[[SRD-Gust|Gust]]'
- - Master
  - '[[SRD-Leer|Leer]]'
- - Master
  - '[[SRD-Payback|Payback]]'
- - Master
  - '[[SRD-Safeguard|Safeguard]]'
- - Master
  - '[[SRD-Wing Attack|Wing Attack]]'
- - Master
  - '[[SRD-Agility|Agility]]'
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Master
  - '[[SRD-Air Slash|Air Slash]]'
- - Master
  - '[[SRD-After You|After You]]'
- - Master
  - '[[SRD-Fiery Wrath|Fiery Wrath]]'
- - Master
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Master
  - '[[SRD-Hurricane|Hurricane]]'
- - Master
  - '[[SRD-Endure|Endure]]'
- - Master
  - '[[SRD-Memento|Memento]]'
- - Master
  - '[[SRD-Sky Attack|Sky Attack]]'
- - Master
  - '[[SRD-Dark Pulse|Dark Pulse]]'
- - Master
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - Master
  - '[[SRD-Hex|Hex]]'
Name: Galarian Moltres (provisional)
Species: '[[SRD-Galarian Moltres (provisional)|Galarian Moltres (provisional)]]'
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
