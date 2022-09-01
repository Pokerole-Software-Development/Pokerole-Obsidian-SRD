---
Accuracy1: SPECIAL
Accuracy2: CHANNEL
Damage1: SPECIAL
Damage2: ''
Description: The Pokemon shoots a heavy projectile, if the foe is under the effects
  of the Dynamax phenomenon all the energy will be concentrated and explode on the
  target.
DmgType: SPECIAL
Effect: If the Foe is under the effects of Dynamax, This Move becomes Lethal and you
  add 4 Extra Dice to the Damage Pool.
Name: Dynamax Cannon
Power: 4
Target: Foe
Type: Dragon
---

#PokeroleSRD/Moves

## `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`