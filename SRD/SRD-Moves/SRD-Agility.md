---
Accuracy1: Dexterity
Accuracy2: Athletic
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: 2
    Stats:
    - Dexterity
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The user relaxes and lightens its body to move faster.
Effect: Increase the User's Dexterity by 2.
Name: Agility
Power: 0
Target: User
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