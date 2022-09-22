---
DexID: '0352'
Moves:
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - Starter
  - '[[SRD-Thief|Thief]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Lick|Lick]]'
- - Beginner
  - '[[SRD-Scratch|Scratch]]'
- - Beginner
  - '[[SRD-Bind|Bind]]'
- - Beginner
  - '[[SRD-Feint|Feint]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Shadow Sneak|Shadow Sneak]]'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Camouflage|Camouflage]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Substitute|Substitute]]'
- - Ace
  - '[[SRD-Shadow Claw|Shadow Claw]]'
- - Ace
  - '[[SRD-Synchronoise|Synchronoise]]'
- - Ace
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Snatch|Snatch]]'
- - Pro
  - '[[SRD-Fake Out|Fake Out]]'
- - Pro
  - '[[SRD-Trick|Trick]]'
Name: Kecleon
Species: '[[SRD-Kecleon|Kecleon]]'
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
