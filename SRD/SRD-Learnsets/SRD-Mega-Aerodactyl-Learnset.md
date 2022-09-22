---
DexID: 0142M1
Moves:
- - Starter
  - '[[SRD-Wing Attack|Wing Attack]]'
- - Starter
  - '[[SRD-Supersonic|Supersonic]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Scary Face|Scary Face]]'
- - Beginner
  - '[[SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Amateur
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Amateur
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Amateur
  - '[[SRD-Roar|Roar]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Iron Head|Iron Head]]'
- - Amateur
  - '[[SRD-Sky Drop|Sky Drop]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - Ace
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Ace
  - '[[SRD-Giga Impact|Giga Impact]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Dragon Breath|Dragon Breath]]'
- - Pro
  - '[[SRD-Roost|Roost]]'
- - Pro
  - '[[SRD-Aqua Tail|Aqua Tail]]'
Name: Mega-Aerodactyl
Species: '[[SRD-Mega-Aerodactyl|Mega-Aerodactyl]]'
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
