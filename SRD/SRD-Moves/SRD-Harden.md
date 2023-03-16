---
Accuracy1: Vitality
Accuracy2: Nature
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: 1
    Stats:
    - Def
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The user stiffins its body and prepares for any incoming attack.
Effect: Increase the User's Defense.
Name: Harden
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