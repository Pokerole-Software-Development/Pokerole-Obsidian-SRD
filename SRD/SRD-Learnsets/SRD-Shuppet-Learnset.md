---
DexID: '0353'
Moves:
- - Starter
  - '[[SRD-Knock Off|Knock Off]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Screech|Screech]]'
- - Beginner
  - '[[SRD-Night Shade|Night Shade]]'
- - Beginner
  - '[[SRD-Spite|Spite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Will-O-Wisp|Will-O-Wisp]]'
- - Amateur
  - '[[SRD-Shadow Sneak|Shadow Sneak]]'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Hex|Hex]]'
- - Amateur
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - Amateur
  - '[[SRD-Snatch|Snatch]]'
- - Amateur
  - '[[SRD-Embargo|Embargo]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Ace
  - '[[SRD-Grudge|Grudge]]'
- - Ace
  - '[[SRD-Trick|Trick]]'
- - Ace
  - '[[SRD-Phantom Force|Phantom Force]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Pro
  - '[[SRD-Role Play|Role Play]]'
- - Pro
  - '[[SRD-Destiny Bond|Destiny Bond]]'
Name: Shuppet
Species: '[[SRD-Shuppet|Shuppet]]'
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
