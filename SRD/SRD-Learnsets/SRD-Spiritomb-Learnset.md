---
DexID: '0442'
Moves:
- - Starter
  - '[[SRD-Curse|Curse]]'
- - Starter
  - '[[SRD-Pursuit|Pursuit]]'
- - Starter
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Starter
  - '[[SRD-Spite|Spite]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Shadow Sneak|Shadow Sneak]]'
- - Beginner
  - '[[SRD-Feint Attack|Feint Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Amateur
  - '[[SRD-Dream Eater|Dream Eater]]'
- - Amateur
  - '[[SRD-Ominous Wind|Ominous Wind]]'
- - Amateur
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Amateur
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Amateur
  - '[[SRD-Dark Pulse|Dark Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Memento|Memento]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Destiny Bond|Destiny Bond]]'
- - Pro
  - '[[SRD-Telekinesis|Telekinesis]]'
- - Pro
  - '[[SRD-Imprison|Imprison]]'
Name: Spiritomb
Species: '[[SRD-Spiritomb|Spiritomb]]'
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
