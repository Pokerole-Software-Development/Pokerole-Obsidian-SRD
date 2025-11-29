---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Grounded
  TerrainEffect: Gravity
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The gravity is intensified, bringing everyone to their knees. Flying
  pokemon are slammed to the ground.
Effect: Flying and Levitating Pokemon can be hit by Ground Type Moves. Lasts 4 Rounds.
Name: Gravity
Power: 0
Target: Battlefield
Type: Psychic
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