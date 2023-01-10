---
Moves:
- - Master
  - '[[SRD-Electric Terrain|Electric Terrain]]'
- - Master
  - '[[SRD-Brave Bird|Brave Bird]]'
- - Master
  - '[[SRD-Power Swap|Power Swap]]'
- - Master
  - '[[SRD-Mean Look|Mean Look]]'
- - Master
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Master
  - '[[SRD-False Swipe|False Swipe]]'
- - Master
  - '[[SRD-Withdraw|Withdraw]]'
- - Master
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - Master
  - '[[SRD-Spark|Spark]]'
- - Master
  - '[[SRD-Shock Wave|Shock Wave]]'
- - Master
  - '[[SRD-Screech|Screech]]'
- - Master
  - '[[SRD-Charge|Charge]]'
- - Master
  - '[[SRD-Wild Charge|Wild Charge]]'
- - Master
  - '[[SRD-Mirror Move|Mirror Move]]'
- - Master
  - '[[SRD-Nature''s Madness|Nature''s Madness]]'
- - Master
  - '[[SRD-Discharge|Discharge]]'
- - Master
  - '[[SRD-Agility|Agility]]'
- - Master
  - '[[SRD-Electro Ball|Electro Ball]]'
- - Master
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Master
  - '[[SRD-Sky Attack|Sky Attack]]'
- - Master
  - '[[SRD-Telekinesis|Telekinesis]]'
- - Master
  - '[[SRD-Defog|Defog]]'
Name: Tapu Koko
Pokedex: '[[SRD-Tapu Koko|Tapu Koko]]'
---

#PokeroleSRD/Learnsets

## `= this.Name` Learnset

**Pokedex Entry:** `= this.Pokedex`

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1] AS Move
FROM #PokeroleSRD/Learnsets
flatten moves as T
where file.path = this.file.path
```
