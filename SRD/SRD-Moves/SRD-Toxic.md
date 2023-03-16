---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: BadlyPoison
Attributes:
  AccuracyReduction: 1
Category: Support
Damage1: ''
Damage2: ''
Description: With a disgusting diet and training, the user learns how to turn its
  fluids into a deadly toxin.
Effect: Badly Poison the Foe. -1 Accuracy.
Name: Toxic
Power: 0
Target: Foe
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