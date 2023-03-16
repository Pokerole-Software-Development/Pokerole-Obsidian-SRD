---
Accuracy1: Will
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: User
    Type: Conversion
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The Pokemon downloads the data of a Move to add it to its code.
Effect: The user changes its type at random.
Name: Conversion
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