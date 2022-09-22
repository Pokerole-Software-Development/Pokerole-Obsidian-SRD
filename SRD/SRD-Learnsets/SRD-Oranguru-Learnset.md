---
DexID: '0764'
Moves:
- - Starter
  - '[[SRD-Confusion|Confusion]]'
- - Starter
  - '[[SRD-After You|After You]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Taunt|Taunt]]'
- - Beginner
  - '[[SRD-Quash|Quash]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Stored Power|Stored Power]]'
- - Amateur
  - '[[SRD-Psych Up|Psych Up]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Amateur
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Amateur
  - '[[SRD-Instruct|Instruct]]'
- - Amateur
  - '[[SRD-Foul Play|Foul Play]]'
- - Amateur
  - '[[SRD-Calm Mind|Calm Mind]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Future Sight|Future Sight]]'
- - Ace
  - '[[SRD-Trick Room|Trick Room]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Psychic Terrain|Psychic Terrain]]'
- - Pro
  - '[[SRD-Wonder Room|Wonder Room]]'
- - Pro
  - '[[SRD-Extrasensory|Extrasensory]]'
Name: Oranguru
Species: '[[SRD-Oranguru|Oranguru]]'
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
