---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -1
    Stats:
    - Accuracy
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: "A mud ball splatters right into the foe\u2019s face, reducing their\
  \ field of vision."
Effect: Single Target. Reduce 1 success to all the Accuracy Rolls of the Target.
Name: Mud Slap
Power: 1
Target: Foe
Type: Ground
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