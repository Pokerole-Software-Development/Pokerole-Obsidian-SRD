---
DexID: 0814
Moves:
- - Starter
  - '[[SRD-Pyro Ball|Pyro Ball]]'
- - Starter
  - '[[SRD-Feint|Feint]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Tackle|Tackle]]'
- - Beginner
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Ember|Ember]]'
- - Amateur
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Amateur
  - '[[SRD-Double Kick|Double Kick]]'
- - Amateur
  - '[[SRD-Flame Charge|Flame Charge]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Headbutt|Headbutt]]'
- - Ace
  - '[[SRD-Counter|Counter]]'
- - Ace
  - '[[SRD-Bounce|Bounce]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Court Change|Court Change]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-High Jump Kick|High Jump Kick]]'
- - Pro
  - '[[SRD-Mega Kick|Mega Kick]]'
- - Pro
  - '[[SRD-Blast Burn|Blast Burn]]'
Name: Cinderace
Species: '[[SRD-Cinderace|Cinderace]]'
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
