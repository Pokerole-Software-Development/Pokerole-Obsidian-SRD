---
DexID: 0720M1
Moves:
- - Master
  - '[[SRD-Flare Blitz|Flare Blitz]]'
- - Master
  - '[[SRD-Take Down|Take Down]]'
- - Master
  - '[[SRD-Mist|Mist]]'
- - Master
  - '[[SRD-Haze|Haze]]'
- - Master
  - '[[SRD-Flame Charge|Flame Charge]]'
- - Master
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Master
  - '[[SRD-Stomp|Stomp]]'
- - Master
  - '[[SRD-Scald|Scald]]'
- - Master
  - '[[SRD-Weather Ball|Weather Ball]]'
- - Master
  - '[[SRD-Body Slam|Body Slam]]'
- - Master
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Master
  - '[[SRD-Overheat|Overheat]]'
- - Master
  - '[[SRD-Explosion|Explosion]]'
- - Master
  - '[[SRD-Steam Eruption|Steam Eruption]]'
- - Master
  - '[[SRD-Solar Beam|Solar Beam]]'
- - Master
  - '[[SRD-Earth Power|Earth Power]]'
- - Master
  - '[[SRD-Superpower|Superpower]]'
Name: Volcanion
Species: '[[SRD-Volcanion|Volcanion]]'
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
