---
Accuracy1: Dexterity
Accuracy2: Stealth
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -1
    Stats:
    - Accuracy
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: Sand to the eyes! A dirty tactic in more ways than one.
Effect: Single Target. Reduce by 1 success to all the Accuracy Rolls of the Target.
Name: Sand Attack
Power: 0
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