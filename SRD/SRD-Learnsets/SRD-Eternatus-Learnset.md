---
Moves:
- - Master
  - '[[SRD-Poison Tail|Poison Tail]]'
- - Master
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Master
  - '[[SRD-Dragon Tail|Dragon Tail]]'
- - Master
  - '[[SRD-Agility|Agility]]'
- - Master
  - '[[SRD-Toxic|Toxic]]'
- - Master
  - '[[SRD-Venoshock|Venoshock]]'
- - Master
  - '[[SRD-Dragon Dance|Dragon Dance]]'
- - Master
  - '[[SRD-Cross Poison|Cross Poison]]'
- - Master
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Master
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Master
  - '[[SRD-Dynamax Cannon|Dynamax Cannon]]'
- - Master
  - '[[SRD-Cosmic Power|Cosmic Power]]'
- - Master
  - '[[SRD-Recover|Recover]]'
- - Master
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - Master
  - '[[SRD-Eternabeam|Eternabeam]]'
- - Master
  - '[[SRD-Light Screen|Light Screen]]'
- - Master
  - '[[SRD-Reflect|Reflect]]'
- - Master
  - '[[SRD-Protect|Protect]]'
Name: Eternatus
Pokedex: '[[SRD-Eternatus|Eternatus]]'
---

#PokeroleSRD/Learnsets

## `= this.Name` Learnset

**Pokedex Entry:** `= this.Pokedex`

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1] AS Move
FROM #PokeroleSRD/Learnsets
flatten moves as T
where file.path = this.file.path
```
