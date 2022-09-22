---
DexID: 0293
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Echoed Voice|Echoed Voice]]'
- - Beginner
  - '[[SRD-Uproar|Uproar]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Astonish|Astonish]]'
- - Amateur
  - '[[SRD-Howl|Howl]]'
- - Amateur
  - '[[SRD-Supersonic|Supersonic]]'
- - Amateur
  - '[[SRD-Stomp|Stomp]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Roar|Roar]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Synchronoise|Synchronoise]]'
- - Ace
  - '[[SRD-Rest|Rest]]'
- - Ace
  - '[[SRD-Sleep Talk|Sleep Talk]]'
- - Ace
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Disarming Voice|Disarming Voice]]'
- - Pro
  - '[[SRD-Fake Tears|Fake Tears]]'
- - Pro
  - '[[SRD-Snore|Snore]]'
Name: Whismur
Species: '[[SRD-Whismur|Whismur]]'
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
