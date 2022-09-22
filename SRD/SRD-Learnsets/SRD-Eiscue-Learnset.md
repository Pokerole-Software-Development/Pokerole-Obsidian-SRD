---
DexID: 0875F1
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Mist|Mist]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Powder Snow|Powder Snow]]'
- - Beginner
  - '[[SRD-Icy Wind|Icy Wind]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Weather Ball|Weather Ball]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Amnesia|Amnesia]]'
- - Amateur
  - '[[SRD-Hail|Hail]]'
- - Amateur
  - '[[SRD-Freeze Dry|Freeze Dry]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Aurora Veil|Aurora Veil]]'
- - Ace
  - '[[SRD-Surf|Surf]]'
- - Ace
  - '[[SRD-Blizzard|Blizzard]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Head Smash|Head Smash]]'
- - Pro
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Pro
  - '[[SRD-Belly Drum|Belly Drum]]'
Name: Eiscue
Species: '[[SRD-Eiscue|Eiscue]]'
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
