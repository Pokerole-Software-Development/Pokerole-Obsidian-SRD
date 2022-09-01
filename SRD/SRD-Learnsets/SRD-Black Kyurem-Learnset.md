---
DexID: 0646F2
Moves:
- - Master
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Master
  - '[[SRD-Dragon Rage|Dragon Rage]]'
- - Master
  - '[[SRD-Imprison|Imprison]]'
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Ice Beam|Ice Beam]]'
- - Master
  - '[[SRD-Dragon Breath|Dragon Breath]]'
- - Master
  - '[[SRD-Slash|Slash]]'
- - Master
  - '[[SRD-Scary Face|Scary Face]]'
- - Master
  - '[[SRD-Glaciate|Glaciate]]'
- - Master
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Master
  - '[[SRD-Noble Roar|Noble Roar]]'
- - Master
  - '[[SRD-Endeavor|Endeavor]]'
- - Master
  - '[[SRD-Blizzard|Blizzard]]'
- - Master
  - '[[SRD-Outrage|Outrage]]'
- - Master
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - Master
  - '[[SRD-Topsy-Turvy|Topsy-Turvy]]'
- - Master
  - '[[SRD-Future Sight|Future Sight]]'
- - Master
  - '[[SRD-Punishment|Punishment]]'
- - Master
  - '[[SRD-Wish|Wish]]'
- - Master
  - '[[SRD-Recover|Recover]]'
- - Master
  - '[[SRD-Fusion Bolt|Fusion Bolt]]'
- - Master
  - '[[SRD-Bolt Strike|Bolt Strike]]'
Name: Black Kyurem
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
