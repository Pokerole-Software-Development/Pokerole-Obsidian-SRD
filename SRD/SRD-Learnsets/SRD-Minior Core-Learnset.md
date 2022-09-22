---
DexID: '0774'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Starter
  - '[[SRD-Rollout|Rollout]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Beginner
  - '[[SRD-Swift|Swift]]'
- - Beginner
  - '[[SRD-Ancient Power|Ancient Power]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Self Destruct|Self Destruct]]'
- - Amateur
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Autotomize|Autotomize]]'
- - Amateur
  - '[[SRD-Cosmic Power|Cosmic Power]]'
- - Amateur
  - '[[SRD-Power Gem|Power Gem]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Shell Smash|Shell Smash]]'
- - Ace
  - '[[SRD-Explosion|Explosion]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Light Screen|Light Screen]]'
- - Pro
  - '[[SRD-Reflect|Reflect]]'
- - Pro
  - '[[SRD-Acrobatics|Acrobatics]]'
Name: Minior Core
Species: '[[SRD-Minior Core|Minior Core]]'
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
