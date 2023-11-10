---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: Target
    Stages: 1
    Stats:
    - Strength
  - Affects: Target
    Stages: 2
    Stats:
    - Dexterity
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The Pokemon has its gears rotate quickly,. Working like a powerful machine.
Effect: Increase the User's Strength by 1 and Dexterity by 2.
Name: Shift Gear
Power: 0
Target: User
Type: Steel
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