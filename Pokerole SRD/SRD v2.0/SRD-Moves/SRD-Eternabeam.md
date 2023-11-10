---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  AccuracyReduction: 1
  Lethal: true
  MustRecharge: true
Category: Special
Damage1: Special
Damage2: ''
Description: The Pokemon shoots an incredibly powerful beam towards the sky. The energy
  released might keep traveling through space thousands of years later.
Effect: Lethal. Must Recharge. -1 Accuracy.
Name: Eternabeam
Power: 7
Target: Foe
Type: Dragon
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