---
Accuracy1: Cool
Accuracy2: Charm
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Confuse
  StatChanges:
  - Affects: Targets
    Stages: 1
    Stats:
    - Special
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The user starts flattering and admiring its opponent. It sure makes them
  feel good about themselves but...why?!
Effect: Single Target. Increase the Target's Special by 1. Confuse the Target.
Name: Flatter
Power: 0
Target: Foe
Type: Dark
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