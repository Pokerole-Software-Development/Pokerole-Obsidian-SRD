---
DexID: 0196
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Starter
  - '[[SRD-Helping Hand|Helping Hand]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Swift|Swift]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Future Sight|Future Sight]]'
- - Amateur
  - '[[SRD-Psych Up|Psych Up]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Morning Sun|Morning Sun]]'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Last Resort|Last Resort]]'
- - Ace
  - '[[SRD-Power Swap|Power Swap]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Wish|Wish]]'
- - Pro
  - '[[SRD-Heal Bell|Heal Bell]]'
- - Pro
  - '[[SRD-Stored Power|Stored Power]]'
Name: Espeon
Species: '[[SRD-Espeon|Espeon]]'
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
