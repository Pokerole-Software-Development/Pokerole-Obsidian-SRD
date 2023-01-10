---
Moves:
- - Starter
  - '[[SRD-Foresight|Foresight]]'
- - Starter
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Starter
  - '[[SRD-Endure|Endure]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Counter|Counter]]'
- - Beginner
  - '[[SRD-Feint|Feint]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Force Palm|Force Palm]]'
- - Amateur
  - '[[SRD-Copycat|Copycat]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Reversal|Reversal]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Ace
  - '[[SRD-Final Gambit|Final Gambit]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Blaze Kick|Blaze Kick]]'
- - Pro
  - '[[SRD-Agility|Agility]]'
- - Pro
  - '[[SRD-Aura Sphere|Aura Sphere]]'
Name: Riolu
Pokedex: '[[SRD-Riolu|Riolu]]'
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
