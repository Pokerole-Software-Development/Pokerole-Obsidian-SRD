---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: This move allows the user to release its power. If the user has any boosts,
  the damage is increased.
Effect: Add 1 Extra Dice of Damage for each Increased attribute the user has (ie.
  Clefairy has 1 Increased Point in Defense and 1 Evasion. Stored Power will have
  2 Extra Dice on the Damage Pool). Up to 7 Dice may be added.
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