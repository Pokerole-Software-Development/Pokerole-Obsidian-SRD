---
DexID: 0685
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Peck|Peck]]'
- - Starter
  - '[[SRD-Constrict|Constrict]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Reflect|Reflect]]'
- - Beginner
  - '[[SRD-Foul Play|Foul Play]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - Amateur
  - '[[SRD-Psywave|Psywave]]'
- - Amateur
  - '[[SRD-Topsy-Turvy|Topsy-Turvy]]'
- - Amateur
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Switcheroo|Switcheroo]]'
- - Amateur
  - '[[SRD-Payback|Payback]]'
- - Amateur
  - '[[SRD-Pluck|Pluck]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Light Screen|Light Screen]]'
- - Ace
  - '[[SRD-Psycho Cut|Psycho Cut]]'
- - Ace
  - '[[SRD-Slash|Slash]]'
- - Ace
  - '[[SRD-Night Slash|Night Slash]]'
- - Ace
  - '[[SRD-Superpower|Superpower]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Power Split|Power Split]]'
- - Pro
  - '[[SRD-Knock Off|Knock Off]]'
- - Pro
  - '[[SRD-Simple Beam|Simple Beam]]'
Name: Inkay
Species: '[[SRD-Inkay|Inkay]]'
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
