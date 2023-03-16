---
Accuracy1: Will
Accuracy2: Channel
AddedEffects: {}
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: The more exhausted the user is, the stronger this attack will become.
  When the Pokemon is at the last of its strength this move can be devastating.
Effect: If User's Will is half spent add 1 Dice to the Damage Roll. If the User's
  Will is depleted add +8 to the Damage Pool.
Name: Trump Card
Power: 2
Target: Foe
Type: Normal
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