---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: -2
    Stats:
    - Special
Attributes:
  AccuracyReduction: -1
Category: Special
Damage1: Special
Damage2: ''
Description: A furious onslaught of sharp leaves blasting against the target. The
  user gives their all in this attack.
Effect: Single Target. Low Accuracy 1. Reduce the User's Special by 2.
Name: Leaf Storm
Power: 6
Target: Foe
Type: Grass
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