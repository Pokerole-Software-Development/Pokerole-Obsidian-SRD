---
DexID: '0777'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Splash|Splash]]'
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Baby-Doll Eyes|Baby-Doll Eyes]]'
- - Beginner
  - '[[SRD-Copycat|Copycat]]'
- - Beginner
  - '[[SRD-Double Team|Double Team]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Play Rough|Play Rough]]'
- - Amateur
  - '[[SRD-Shadow Sneak|Shadow Sneak]]'
- - Amateur
  - '[[SRD-Mimic|Mimic]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Charm|Charm]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Shadow Claw|Shadow Claw]]'
- - Amateur
  - '[[SRD-Hone Claws|Hone Claws]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Wood Hammer|Wood Hammer]]'
- - Ace
  - '[[SRD-Pain Split|Pain Split]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Destiny Bond|Destiny Bond]]'
- - Pro
  - '[[SRD-Curse|Curse]]'
- - Pro
  - '[[SRD-Grudge|Grudge]]'
Name: Mimikyu
Species: '[[SRD-Mimikyu|Mimikyu]]'
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
