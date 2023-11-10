---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects: {}
Attributes: {}
Category: Physical
Damage1: Strength
Damage2: ''
Description: The Pokemon charges with its beak and pecks its foe, if the foe is not
  fast it will be zapped by a jolt of electricity.
Effect: If the Target hasn't had a Turn this Round, add 2 Extra Dice to the Damage
  pool.
Name: Bolt Beak
Power: 2
Target: Foe
Type: Electric
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