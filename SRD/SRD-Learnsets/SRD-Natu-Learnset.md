---
DexID: '0177'
Moves:
- - Starter
  - '[[SRD-Peck|Peck]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Night Shade|Night Shade]]'
- - Beginner
  - '[[SRD-Teleport|Teleport]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - Amateur
  - '[[SRD-Miracle Eye|Miracle Eye]]'
- - Amateur
  - '[[SRD-Me First|Me First]]'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Ominous Wind|Ominous Wind]]'
- - Amateur
  - '[[SRD-Psycho Shift|Psycho Shift]]'
- - Amateur
  - '[[SRD-Stored Power|Stored Power]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Future Sight|Future Sight]]'
- - Ace
  - '[[SRD-Wish|Wish]]'
- - Ace
  - '[[SRD-Power Swap|Power Swap]]'
- - Ace
  - '[[SRD-Guard Swap|Guard Swap]]'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Pain Split|Pain Split]]'
- - Pro
  - '[[SRD-Twister|Twister]]'
- - Pro
  - '[[SRD-Haze|Haze]]'
Name: Natu
Species: '[[SRD-Natu|Natu]]'
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
