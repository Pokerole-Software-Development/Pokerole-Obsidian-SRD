---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Poison
Attributes:
  AccuracyReduction: 1
Category: Support
Damage1: ''
Damage2: ''
Description: The Pokemon releases a big cloud of toxic gas, anyone who takes a breath
  will start coughing violently. They should seek a doctor immediately.
Effect: Poison those affected. -1 Accuracy.
Name: Poison Gas
Power: 0
Target: All Foes
Type: Poison
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