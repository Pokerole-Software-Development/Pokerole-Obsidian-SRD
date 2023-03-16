---
Accuracy1: Insight
Accuracy2: Nature
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: 1
    Stats:
    - Strength
    - Accuracy
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The Pokemon sharpens its claws to perform more precise attacks.
Effect: Increase the User's Strength and Accuracy.
Name: Hone Claws
Power: 0
Target: User
Type: Dark
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