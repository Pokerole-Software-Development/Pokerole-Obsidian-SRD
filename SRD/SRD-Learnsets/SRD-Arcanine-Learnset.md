---
DexID: 0059
Moves:
- - Starter
  - '[[SRD-Roar|Roar]]'
- - Starter
  - '[[SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Amateur
  - '[[SRD-Fire Fang|Fire Fang]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Burn Up|Burn Up]]'
- - Ace
  - '[[SRD-Extreme Speed|Extreme Speed]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Morning Sun|Morning Sun]]'
- - Pro
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Pro
  - '[[SRD-Wild Charge|Wild Charge]]'
Name: Arcanine
Species: '[[SRD-Arcanine|Arcanine]]'
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
