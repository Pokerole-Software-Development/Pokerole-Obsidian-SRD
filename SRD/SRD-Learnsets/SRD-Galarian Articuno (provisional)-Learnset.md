---
DexID: 0144G
Moves:
- - Master
  - '[[SRD-Gust|Gust]]'
- - Master
  - '[[SRD-Psycho Shift|Psycho Shift]]'
- - Master
  - '[[SRD-Confusion|Confusion]]'
- - Master
  - '[[SRD-Reflect|Reflect]]'
- - Master
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Master
  - '[[SRD-Agility|Agility]]'
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Tailwind|Tailwind]]'
- - Master
  - '[[SRD-Psycho Cut|Psycho Cut]]'
- - Master
  - '[[SRD-Recover|Recover]]'
- - Master
  - '[[SRD-Freezing Glare|Freezing Glare]]'
- - Master
  - '[[SRD-Dream Eater|Dream Eater]]'
- - Master
  - '[[SRD-Hurricane|Hurricane]]'
- - Master
  - '[[SRD-Mind Reader|Mind Reader]]'
- - Master
  - '[[SRD-Future Sight|Future Sight]]'
- - Master
  - '[[SRD-Trick Room|Trick Room]]'
- - Master
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - Master
  - '[[SRD-Expanding Force|Expanding Force]]'
- - Master
  - '[[SRD-Fly|Fly]]'
Name: Galarian Articuno (provisional)
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
