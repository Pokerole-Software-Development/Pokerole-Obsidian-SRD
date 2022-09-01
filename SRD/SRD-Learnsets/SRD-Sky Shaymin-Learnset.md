---
DexID: 0492F1
Moves:
- - Master
  - '[[SRD-Growth|Growth]]'
- - Master
  - '[[SRD-Magical Leaf|Magical Leaf]]'
- - Master
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Master
  - '[[SRD-Synthesis|Synthesis]]'
- - Master
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Master
  - '[[SRD-Natural Gift|Natural Gift]]'
- - Master
  - '[[SRD-Worry Seed|Worry Seed]]'
- - Master
  - '[[SRD-Air Slash|Air Slash]]'
- - Master
  - '[[SRD-Energy Ball|Energy Ball]]'
- - Master
  - '[[SRD-Sweet Kiss|Sweet Kiss]]'
- - Master
  - '[[SRD-Leaf Storm|Leaf Storm]]'
- - Master
  - '[[SRD-Seed Flare|Seed Flare]]'
- - Master
  - '[[SRD-Endeavor|Endeavor]]'
- - Master
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Master
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Master
  - '[[SRD-Tailwind|Tailwind]]'
Name: Sky Shaymin
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
