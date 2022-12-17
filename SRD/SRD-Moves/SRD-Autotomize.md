---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Target
    Type: Autotomize
  StatChanges:
  - Affects: User
    Stages: 2
    Stats:
    - Dexterity
Attributes: {}
Damage1: ''
Damage2: ''
Description: The Pokemon sheds pieces and starts rotating other parts of its body
  for easier and lighter movement.
DmgType: Support
Effect: Increase the User's Dexterity by 2. User's weight is halved for the rest of
  Scene.
Name: Autotomize
Power: 0
Target: User
Type: Steel
---

#PokeroleSRD/Moves

### `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`