---
DexID: '0361'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Powder Snow|Powder Snow]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Double Team|Double Team]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Protect|Protect]]'
- - Amateur
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Amateur
  - '[[SRD-Frost Breath|Frost Breath]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Ice Shard|Ice Shard]]'
- - Ace
  - '[[SRD-Hail|Hail]]'
- - Ace
  - '[[SRD-Blizzard|Blizzard]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Weather Ball|Weather Ball]]'
- - Pro
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Pro
  - '[[SRD-Fake Tears|Fake Tears]]'
Name: Snorunt
Species: '[[SRD-Snorunt|Snorunt]]'
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
