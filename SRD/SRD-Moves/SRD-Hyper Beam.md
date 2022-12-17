---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  AccuracyReduction: 1
  Lethal: true
  MustRecharge: true
Damage1: Special
Damage2: ''
Description: The Pokemon casts an incredible beam that leaves a giant trail of destruction
  behind. The user is left exhausted.
DmgType: Special
Effect: Must Recharge. Lethal. -1 Accuracy.
Name: Hyper Beam
Power: 6
Target: Foe
Type: Normal
---

#PokeroleSRD/Moves

### `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`