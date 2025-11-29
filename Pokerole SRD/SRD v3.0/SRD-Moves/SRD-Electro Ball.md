---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  ProjectileMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: An orb of electricity is hurled against the target, the faster the user
  dashes, the more momentum the orb gets.
Effect: Single Target. Projectile Move. *Add 1 Extra Die to the Damage Pool of the
  user for every Point on Dexterity it has that surpasses the Foe's. Up to 4 Dice
  might be added this way.
Name: Electro Ball
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