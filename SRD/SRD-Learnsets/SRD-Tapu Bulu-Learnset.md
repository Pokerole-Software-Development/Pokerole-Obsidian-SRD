---
DexID: 0788
Moves:
- - Master
  - '[[SRD-Grassy Terrain|Grassy Terrain]]'
- - Master
  - '[[SRD-Wood Hammer|Wood Hammer]]'
- - Master
  - '[[SRD-Superpower|Superpower]]'
- - Master
  - '[[SRD-Mean Look|Mean Look]]'
- - Master
  - '[[SRD-Disable|Disable]]'
- - Master
  - '[[SRD-Whirlwind|Whirlwind]]'
- - Master
  - '[[SRD-Withdraw|Withdraw]]'
- - Master
  - '[[SRD-Leafage|Leafage]]'
- - Master
  - '[[SRD-Horn Attack|Horn Attack]]'
- - Master
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Master
  - '[[SRD-Scary Face|Scary Face]]'
- - Master
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Master
  - '[[SRD-Horn Leech|Horn Leech]]'
- - Master
  - '[[SRD-Rototiller|Rototiller]]'
- - Master
  - '[[SRD-Nature''s Madness|Nature''s Madness]]'
- - Master
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Master
  - '[[SRD-Megahorn|Megahorn]]'
- - Master
  - '[[SRD-Skull Bash|Skull Bash]]'
- - Master
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Master
  - '[[SRD-Dual Chop|Dual Chop]]'
- - Master
  - '[[SRD-Focus Punch|Focus Punch]]'
- - Master
  - '[[SRD-Worry Seed|Worry Seed]]'
Name: Tapu Bulu
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
