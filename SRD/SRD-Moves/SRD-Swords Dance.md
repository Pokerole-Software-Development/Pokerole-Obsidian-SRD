---
Accuracy1: Dexterity
Accuracy2: Perform
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: 2
    Stats:
    - Strength
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The Pokemon makes a dance that raises its battle spirit.
Effect: Increase the User's Strength by 2.
Name: Swords Dance
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