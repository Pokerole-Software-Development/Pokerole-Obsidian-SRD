---
DexID: 0787
Moves:
- - Master
  - '[[SRD-Misty Terrain|Misty Terrain]]'
- - Master
  - '[[SRD-Moonblast|Moonblast]]'
- - Master
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - Master
  - '[[SRD-Mean Look|Mean Look]]'
- - Master
  - '[[SRD-Haze|Haze]]'
- - Master
  - '[[SRD-Mist|Mist]]'
- - Master
  - '[[SRD-Withdraw|Withdraw]]'
- - Master
  - '[[SRD-Water Gun|Water Gun]]'
- - Master
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Master
  - '[[SRD-Whirlpool|Whirlpool]]'
- - Master
  - '[[SRD-Soak|Soak]]'
- - Master
  - '[[SRD-Refresh|Refresh]]'
- - Master
  - '[[SRD-Brine|Brine]]'
- - Master
  - '[[SRD-Defog|Defog]]'
- - Master
  - '[[SRD-Nature''s Madness|Nature''s Madness]]'
- - Master
  - '[[SRD-Muddy Water|Muddy Water]]'
- - Master
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Master
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Master
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Master
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Master
  - '[[SRD-Wonder Room|Wonder Room]]'
- - Master
  - '[[SRD-Knock Off|Knock Off]]'
Name: Tapu Fini
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
