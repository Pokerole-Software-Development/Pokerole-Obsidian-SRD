---
DexID: '0244'
Moves:
- - Master
  - '[[SRD-Bite|Bite]]'
- - Master
  - '[[SRD-Leer|Leer]]'
- - Master
  - '[[SRD-Ember|Ember]]'
- - Master
  - '[[SRD-Roar|Roar]]'
- - Master
  - '[[SRD-Fire Spin|Fire Spin]]'
- - Master
  - '[[SRD-Stomp|Stomp]]'
- - Master
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Master
  - '[[SRD-Swagger|Swagger]]'
- - Master
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Master
  - '[[SRD-Lava Plume|Lava Plume]]'
- - Master
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Master
  - '[[SRD-Fire Blast|Fire Blast]]'
- - Master
  - '[[SRD-Calm Mind|Calm Mind]]'
- - Master
  - '[[SRD-Eruption|Eruption]]'
- - Master
  - '[[SRD-Double Team|Double Team]]'
- - Master
  - '[[SRD-Substitute|Substitute]]'
- - Master
  - '[[SRD-Will-O-Wisp|Will-O-Wisp]]'
- - Master
  - '[[SRD-Rock Smash|Rock Smash]]'
- - Master
  - '[[SRD-Mimic|Mimic]]'
- - Master
  - '[[SRD-Curse|Curse]]'
- - Master
  - '[[SRD-Sacred Fire|Sacred Fire]]'
Name: Entei
Species: '[[SRD-Entei|Entei]]'
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
