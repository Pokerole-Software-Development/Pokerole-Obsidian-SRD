---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: This move allows the user to release its power. If the user has any boosts,
  the damage is increased.
Effect: Single Target. *Add 1 Die to the Damage Pool of this Move for each Attribute
  increase the User has, up to a maximum of 7 total Dice. (eg The User has 2 increased
  Points of Defense, add 2 Damage Dice.)
Name: Stored Power
Power: 1
Target: Foe
Type: Psychic
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