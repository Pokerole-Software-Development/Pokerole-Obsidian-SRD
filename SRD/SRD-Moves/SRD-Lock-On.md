---
Accuracy1: Insight
Accuracy2: Alert
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: LockOn
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The Pokemon's eyes zoom at a moving target to ensure that the next attack
  will be dealt with precision.
Effect: The next attack the user performs has 2 automatic unremovable successes on
  its Accuracy Roll.
Name: Lock-On
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