---
DexID: 0408
Moves:
- - Starter
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Take Down|Take Down]]'
- - Beginner
  - '[[SRD-Pursuit|Pursuit]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Assurance|Assurance]]'
- - Amateur
  - '[[SRD-Chip Away|Chip Away]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Ace
  - '[[SRD-Screech|Screech]]'
- - Ace
  - '[[SRD-Head Smash|Head Smash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Superpower|Superpower]]'
- - Pro
  - '[[SRD-Iron Head|Iron Head]]'
- - Pro
  - '[[SRD-Hammer Arm|Hammer Arm]]'
Name: Cranidos
Species: '[[SRD-Cranidos|Cranidos]]'
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
