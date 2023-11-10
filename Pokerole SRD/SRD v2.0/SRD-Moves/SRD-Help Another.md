---
Accuracy1: ''
Accuracy2: Varies
AddedEffects: {}
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: ''
Effect: Roll your Accuracy as if it was Chance Dice. If Successful, add one die to
  the Action of an Ally. Up to 6 dice may be added this way.
Name: Help Another
Power: 0
Target: One Ally
Type: Typeless
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