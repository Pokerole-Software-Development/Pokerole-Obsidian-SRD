---
DexID: 0103A
Moves:
- - Starter
  - '[[SRD-Barrage|Barrage]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Beginner
  - '[[SRD-Confusion|Confusion]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Seed Bomb|Seed Bomb]]'
- - Amateur
  - '[[SRD-Egg Bomb|Egg Bomb]]'
- - Amateur
  - '[[SRD-Psyshock|Psyshock]]'
- - Amateur
  - '[[SRD-Dragon Hammer|Dragon Hammer]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Wood Hammer|Wood Hammer]]'
- - Ace
  - '[[SRD-Leaf Storm|Leaf Storm]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Dragon Tail|Dragon Tail]]'
- - Pro
  - '[[SRD-Ingrain|Ingrain]]'
- - Pro
  - '[[SRD-Giga Impact|Giga Impact]]'
Name: Alolan Exeggutor
Species: '[[SRD-Alolan Exeggutor|Alolan Exeggutor]]'
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
