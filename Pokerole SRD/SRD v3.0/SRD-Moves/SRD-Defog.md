---
Accuracy1: Insight
Accuracy2: Nature
AddedEffects: {}
Attributes:
  DestroyShield: true
  ResetTerrain: true
Category: Support
Damage1: ''
Damage2: ''
Description: A strong wind sweeps out the battle field, removing anything from bad
  weather to scattered objects and even invisible barriers.
Effect: Target Battlefield. Remove all Force Fields, Entry Hazards and Terrains (Misty
  Terrain, Electric Terrain, etc.) from the Battlefield.
Name: Defog
Power: 0
Target: Battlefield
Type: Flying
---

#PokeroleSRD/Moves

### `= this.name`
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Category          | Power          |
| ------------- | --------------- | ----------------  | -------------- |
| `= this.Type` | `= this.Target` | `= this.Category` | `= this.Power` | 

**Effect:** `= this.Effect`