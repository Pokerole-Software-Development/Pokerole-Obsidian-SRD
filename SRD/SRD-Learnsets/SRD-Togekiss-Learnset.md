---
Moves:
- - Starter
  - '[[SRD-After You|After You]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Extreme Speed|Extreme Speed]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Sky Attack|Sky Attack]]'
- - Amateur
  - '[[SRD-Aura Sphere|Aura Sphere]]'
- - Amateur
  - '[[SRD-Air Slash|Air Slash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Pro
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - Pro
  - '[[SRD-Water Pulse|Water Pulse]]'
Name: Togekiss
Pokedex: '[[SRD-Togekiss|Togekiss]]'
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
