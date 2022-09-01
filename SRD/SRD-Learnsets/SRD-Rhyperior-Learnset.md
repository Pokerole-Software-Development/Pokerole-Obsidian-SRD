---
DexID: '0464'
Moves:
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Starter
  - '[[SRD-Horn Attack|Horn Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Stomp|Stomp]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Poison Jab|Poison Jab]]'
- - Amateur
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Rock Blast|Rock Blast]]'
- - Amateur
  - '[[SRD-Chip Away|Chip Away]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Amateur
  - '[[SRD-Drill Run|Drill Run]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Stone Edge|Stone Edge]]'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Horn Drill|Horn Drill]]'
- - Ace
  - '[[SRD-Megahorn|Megahorn]]'
- - Ace
  - '[[SRD-Rock Wrecker|Rock Wrecker]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Guard Split|Guard Split]]'
- - Pro
  - '[[SRD-Smart Strike|Smart Strike]]'
- - Pro
  - '[[SRD-Dragon Rush|Dragon Rush]]'
Name: Rhyperior
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
