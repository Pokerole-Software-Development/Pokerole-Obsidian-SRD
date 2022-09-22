---
DexID: 0219
Moves:
- - Starter
  - '[[SRD-Yawn|Yawn]]'
- - Starter
  - '[[SRD-Smog|Smog]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Rock Throw|Rock Throw]]'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - Amateur
  - '[[SRD-Harden|Harden]]'
- - Amateur
  - '[[SRD-Incinerate|Incinerate]]'
- - Amateur
  - '[[SRD-Recover|Recover]]'
- - Amateur
  - '[[SRD-Clear Smog|Clear Smog]]'
- - Amateur
  - '[[SRD-Flame Burst|Flame Burst]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[SRD-Amnesia|Amnesia]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Lava Plume|Lava Plume]]'
- - Ace
  - '[[SRD-Earth Power|Earth Power]]'
- - Ace
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Ace
  - '[[SRD-Shell Smash|Shell Smash]]'
- - Ace
  - '[[SRD-Flamethrower|Flamethrower]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Inferno|Inferno]]'
- - Pro
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Pro
  - '[[SRD-Self Destruct|Self Destruct]]'
Name: Magcargo
Species: '[[SRD-Magcargo|Magcargo]]'
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
