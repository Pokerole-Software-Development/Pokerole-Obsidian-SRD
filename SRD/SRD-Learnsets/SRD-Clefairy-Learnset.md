---
DexID: '0035'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Pound|Pound]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sing|Sing]]'
- - Beginner
  - '[[SRD-Disarming Voice|Disarming Voice]]'
- - Beginner
  - '[[SRD-Double Slap|Double Slap]]'
- - Beginner
  - '[[SRD-Encore|Encore]]'
- - Beginner
  - '[[SRD-Defense Curl|Defense Curl]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Metronome|Metronome]]'
- - Amateur
  - '[[SRD-Bestow|Bestow]]'
- - Amateur
  - '[[SRD-Follow Me|Follow Me]]'
- - Amateur
  - '[[SRD-Minimize|Minimize]]'
- - Amateur
  - '[[SRD-Wake-Up Slap|Wake-Up Slap]]'
- - Amateur
  - '[[SRD-After You|After You]]'
- - Amateur
  - '[[SRD-Stored Power|Stored Power]]'
- - Amateur
  - '[[SRD-Spotlight|Spotlight]]'
- - Amateur
  - '[[SRD-Cosmic Power|Cosmic Power]]'
- - Amateur
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Body Slam|Body Slam]]'
- - Ace
  - '[[SRD-Moonlight|Moonlight]]'
- - Ace
  - '[[SRD-Moonblast|Moonblast]]'
- - Ace
  - '[[SRD-Gravity|Gravity]]'
- - Ace
  - '[[SRD-Meteor Mash|Meteor Mash]]'
- - Ace
  - '[[SRD-Healing Wish|Healing Wish]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Swift|Swift]]'
- - Pro
  - '[[SRD-Heal Bell|Heal Bell]]'
- - Pro
  - '[[SRD-Heal Pulse|Heal Pulse]]'
Name: Clefairy
Species: '[[SRD-Clefairy|Clefairy]]'
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
