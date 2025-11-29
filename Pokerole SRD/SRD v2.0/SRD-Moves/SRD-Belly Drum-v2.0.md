---
Accuracy1: Tough
Accuracy2: Perform
AddedEffects:
  FixedDamage:
    Target: Targets
    Type: MaxHpPercentage
    Value: 0.5
  StatChanges:
  - Affects: User
    Stages: 3
    Stats:
    - Strength
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The Pokemon Roars a war cry while hitting its Belly.
Effect: User deals Damage to itself equal to Half of its total HP rounded down. Increase
  User's Strength by 3.
Name: Belly Drum
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