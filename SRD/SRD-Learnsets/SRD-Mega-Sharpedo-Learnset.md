---
DexID: 0319M1
Moves:
- - Starter
  - '[[SRD-Bite|Bite]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Beginner
  - '[[SRD-Feint|Feint]]'
- - Beginner
  - '[[SRD-Rage|Rage]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Night Slash|Night Slash]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - Amateur
  - '[[SRD-Taunt|Taunt]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Poison Fang|Poison Fang]]'
- - Ace
  - '[[SRD-Assurance|Assurance]]'
- - Ace
  - '[[SRD-Agility|Agility]]'
- - Ace
  - '[[SRD-Skull Bash|Skull Bash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Pro
  - '[[SRD-Psychic Fangs|Psychic Fangs]]'
- - Pro
  - '[[SRD-Spite|Spite]]'
Name: Mega-Sharpedo
Species: '[[SRD-Mega-Sharpedo|Mega-Sharpedo]]'
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
