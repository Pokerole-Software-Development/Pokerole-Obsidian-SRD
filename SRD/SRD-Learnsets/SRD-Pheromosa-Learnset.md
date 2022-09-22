---
DexID: 0796
Moves:
- - Master
  - '[[SRD-Quiver Dance|Quiver Dance]]'
- - Master
  - '[[SRD-Quick Guard|Quick Guard]]'
- - Master
  - '[[SRD-Low Kick|Low Kick]]'
- - Master
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - Master
  - '[[SRD-Leer|Leer]]'
- - Master
  - '[[SRD-Double Kick|Double Kick]]'
- - Master
  - '[[SRD-Swift|Swift]]'
- - Master
  - '[[SRD-Stomp|Stomp]]'
- - Master
  - '[[SRD-Feint|Feint]]'
- - Master
  - '[[SRD-Silver Wind|Silver Wind]]'
- - Master
  - '[[SRD-Bounce|Bounce]]'
- - Master
  - '[[SRD-Jump Kick|Jump Kick]]'
- - Master
  - '[[SRD-Agility|Agility]]'
- - Master
  - '[[SRD-Triple Kick|Triple Kick]]'
- - Master
  - '[[SRD-Lunge|Lunge]]'
- - Master
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - Master
  - '[[SRD-Me First|Me First]]'
- - Master
  - '[[SRD-High Jump Kick|High Jump Kick]]'
- - Master
  - '[[SRD-Speed Swap|Speed Swap]]'
- - Master
  - '[[SRD-Throat Chop|Throat Chop]]'
- - Master
  - '[[SRD-Shock Wave|Shock Wave]]'
- - Master
  - '[[SRD-Outrage|Outrage]]'
Name: Pheromosa
Species: '[[SRD-Pheromosa|Pheromosa]]'
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
