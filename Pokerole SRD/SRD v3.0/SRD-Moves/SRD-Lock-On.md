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
Description: "The Pok\xE9mon\u2019s eyes zoom into a moving target to strike with\
  \ precision at the next opportunity."
Effect: Target Self. The Next Move the User Performs has 2 automatic successes added
  on their Accuracy Roll.
Name: Lock-On
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