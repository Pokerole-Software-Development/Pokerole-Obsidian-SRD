---
DexID: 0866
Moves:
- - Starter
  - '[[SRD-Peck|Peck]]'
- - Starter
  - '[[SRD-Sand Attack|Sand Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Leer|Leer]]'
- - Beginner
  - '[[SRD-Fury Cutter|Fury Cutter]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Rock Smash|Rock Smash]]'
- - Amateur
  - '[[SRD-Brutal Swing|Brutal Swing]]'
- - Amateur
  - '[[SRD-Detect|Detect]]'
- - Amateur
  - '[[SRD-Knock Off|Knock Off]]'
- - Amateur
  - '[[SRD-Defog|Defog]]'
- - Amateur
  - '[[SRD-Brick Break|Brick Break]]'
- - Amateur
  - '[[SRD-Slam|Slam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Swords Dance|Swords Dance]]'
- - Ace
  - '[[SRD-First Impression|First Impression]]'
- - Ace
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Ace
  - '[[SRD-Leaf Blade|Leaf Blade]]'
- - Ace
  - '[[SRD-Final Gambit|Final Gambit]]'
- - Ace
  - '[[SRD-Brave Bird|Brave Bird]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Meteor Assault|Meteor Assault]]'
- - Pro
  - '[[SRD-Simple Beam|Simple Beam]]'
- - Pro
  - '[[SRD-Endure|Endure]]'
- - Pro
  - '[[SRD-Focus Energy|Focus Energy]]'
Name: Sirfetch'd
Species: '[[SRD-Sirfetch''d|Sirfetch''d]]'
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
