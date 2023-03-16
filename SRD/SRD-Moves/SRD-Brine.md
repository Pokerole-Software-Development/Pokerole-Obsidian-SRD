---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: The user blasts the foe with extremely dense water, if the target is
  tired he may be swept away easily by the pressure.
Effect: If the foe is at half HP or less, add 3 Extra Dice to the Damage Pool.
Name: Brine
Power: 2
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