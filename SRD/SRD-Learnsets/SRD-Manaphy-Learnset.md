---
DexID: 0490
Moves:
- - Master
  - '[[SRD-Tail Glow|Tail Glow]]'
- - Master
  - '[[SRD-Bubble|Bubble]]'
- - Master
  - '[[SRD-Water Sport|Water Sport]]'
- - Master
  - '[[SRD-Charm|Charm]]'
- - Master
  - '[[SRD-Supersonic|Supersonic]]'
- - Master
  - '[[SRD-Bubble Beam|Bubble Beam]]'
- - Master
  - '[[SRD-Acid Armor|Acid Armor]]'
- - Master
  - '[[SRD-Whirlpool|Whirlpool]]'
- - Master
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Master
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Master
  - '[[SRD-Dive|Dive]]'
- - Master
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Master
  - '[[SRD-Surf|Surf]]'
- - Master
  - '[[SRD-Heart Swap|Heart Swap]]'
- - Master
  - '[[SRD-Liquidation|Liquidation]]'
- - Master
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Master
  - '[[SRD-Bounce|Bounce]]'
Name: Manaphy
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
