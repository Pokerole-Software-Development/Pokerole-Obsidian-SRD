---
Accuracy1: Will
Accuracy2: Channel
AddedEffects: {}
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: "You can\u2019t give up until you have given your all. And just as everyone\
  \ thinks you are done for, you still the last card in your hand."
Effect: Single Target. *If the User's Will Points are at half or less, add 2 Extra
  Dice to the Damage pool. **If the User's Will points are depleted, add 8 Extra Dice
  to the Damage pool of this Move instead.
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