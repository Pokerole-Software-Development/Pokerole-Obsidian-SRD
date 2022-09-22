---
DexID: '0645'
Moves:
- - Master
  - '[[SRD-Dragon Rage|Dragon Rage]]'
- - Master
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Master
  - '[[SRD-Imprison|Imprison]]'
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Thunderbolt|Thunderbolt]]'
- - Master
  - '[[SRD-Dragon Breath|Dragon Breath]]'
- - Master
  - '[[SRD-Slash|Slash]]'
- - Master
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Master
  - '[[SRD-Fusion Bolt|Fusion Bolt]]'
- - Master
  - '[[SRD-Dragon Claw|Dragon Claw]]'
- - Master
  - '[[SRD-Noble Roar|Noble Roar]]'
- - Master
  - '[[SRD-Crunch|Crunch]]'
- - Master
  - '[[SRD-Thunder|Thunder]]'
- - Master
  - '[[SRD-Outrage|Outrage]]'
- - Master
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - Master
  - '[[SRD-Bolt Strike|Bolt Strike]]'
- - Master
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - Master
  - '[[SRD-Wish|Wish]]'
- - Master
  - '[[SRD-Future Sight|Future Sight]]'
- - Master
  - '[[SRD-Topsy-Turvy|Topsy-Turvy]]'
Name: Zekrom
Species: '[[SRD-Zekrom|Zekrom]]'
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
