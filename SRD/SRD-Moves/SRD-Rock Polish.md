---
Accuracy1: Dexterity
Accuracy2: Channel
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
Description: The user polishes the rough ends of its rock body for easier and faster
  movement.
Effect: Increase User's Dexterity by 2.
Name: Rock Polish
Power: 0
Target: User
Type: Rock
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