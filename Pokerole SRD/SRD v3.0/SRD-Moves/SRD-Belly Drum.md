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
Description: With an angry war cry the user hits their belly as drums of war.
Effect: Target Self. Roll half of the User's HP as Typeless Damage Dice to itself,
  ignore defenses. Increase User's Strengt by 3.
Name: Belly Drum
Power: 0
Target: Self
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