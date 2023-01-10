---
Moves:
- - Starter
  - '[[SRD-Sketch|Sketch]]'
- - Starter
  - '[[SRD-Sketch|Sketch]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sketch|Sketch]]'
- - Beginner
  - '[[SRD-Sketch|Sketch]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Sketch|Sketch]]'
- - Amateur
  - '[[SRD-Sketch|Sketch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Sketch|Sketch]]'
- - Ace
  - '[[SRD-Sketch|Sketch]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Sketch|Sketch]]'
- - Pro
  - '[[SRD-Sketch|Sketch]]'
Name: Smeargle
Pokedex: '[[SRD-Smeargle|Smeargle]]'
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
