---
DexID: 0813
Moves:
- - Starter
  - '[[SRD-Drum Beating|Drum Beating]]'
- - Starter
  - '[[SRD-Double Hit|Double Hit]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Grassy Terrain|Grassy Terrain]]'
- - Beginner
  - '[[SRD-Noble Roar|Noble Roar]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Scratch|Scratch]]'
- - Amateur
  - '[[SRD-Growl|Growl]]'
- - Amateur
  - '[[SRD-Branch Poke|Branch Poke]]'
- - Amateur
  - '[[SRD-Taunt|Taunt]]'
- - Amateur
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Knock Off|Knock Off]]'
- - Ace
  - '[[SRD-Slam|Slam]]'
- - Ace
  - '[[SRD-Uproar|Uproar]]'
- - Ace
  - '[[SRD-Wood Hammer|Wood Hammer]]'
- - Ace
  - '[[SRD-Endeavor|Endeavor]]'
- - Ace
  - '[[SRD-Boomburst|Boomburst]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Growth|Growth]]'
- - Pro
  - '[[SRD-Nature Power|Nature Power]]'
- - Pro
  - '[[SRD-Frenzy Plant|Frenzy Plant]]'
Name: Rillaboom
---

#PokeroleSRD/Learnsets

## `= this.Name` Learnset

**DexID:** `= this.DexID`

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1] AS Move
FROM "Pokerole SRD/SRD-Learnsets"
flatten moves as T
where file.path = this.file.path
```
