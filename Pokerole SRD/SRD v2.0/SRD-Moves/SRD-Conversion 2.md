---
Accuracy1: Will
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: User
    Type: Conversion2
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The Pokemon downloads the data of a move that was used against it. Change
  the code of the user to a type resistant to the that move.
Effect: After being dealt damage, choose a Type resistant to the Type of that attack.
  That's the Type of the User until it uses this Move again.
Name: Conversion 2
Power: 0
Target: User
Type: Normal
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