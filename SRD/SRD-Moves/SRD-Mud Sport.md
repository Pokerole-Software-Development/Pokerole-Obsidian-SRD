---
Accuracy1: Special
Accuracy2: Nature
AddedEffects:
  TerrainEffect: MudSport
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The user covers everything with mud, reducing the effectiveness of electric
  attacks made on the field.
Effect: For the next 4 Rounds Electric Type attacks won't add their Power to the Damage
  Pool.
Name: Mud Sport
Power: 0
Target: Battlefield
Type: Ground
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