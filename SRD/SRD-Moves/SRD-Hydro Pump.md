---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  AccuracyReduction: 1
Category: Special
Damage1: Special
Damage2: ''
Description: The user builds up pressure inside its body and then releases a tremendous
  amount of water at the target.
Effect: -1 Accuracy.
Name: Hydro Pump
Power: 5
Target: Foe
Type: Water
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