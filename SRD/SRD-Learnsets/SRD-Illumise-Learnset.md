---
DexID: '0314'
Moves:
- - Starter
  - '[[SRD-Play Nice|Play Nice]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Beginner
  - '[[SRD-Charm|Charm]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Moonlight|Moonlight]]'
- - Amateur
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Amateur
  - '[[SRD-Struggle Bug|Struggle Bug]]'
- - Amateur
  - '[[SRD-Wish|Wish]]'
- - Amateur
  - '[[SRD-Encore|Encore]]'
- - Amateur
  - '[[SRD-Flatter|Flatter]]'
- - Amateur
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Amateur
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - Ace
  - '[[SRD-Play Rough|Play Rough]]'
- - Ace
  - '[[SRD-Covet|Covet]]'
- - Ace
  - '[[SRD-Infestation|Infestation]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Captivate|Captivate]]'
- - Pro
  - '[[SRD-Tailwind|Tailwind]]'
- - Pro
  - '[[SRD-Silver Wind|Silver Wind]]'
Name: Illumise
Species: '[[SRD-Illumise|Illumise]]'
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
