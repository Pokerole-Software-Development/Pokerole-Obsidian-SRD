---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 3
    Type: Burn2
Attributes:
  Lethal: true
  ProjectileMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: The User torches everything around itself in a sudden burst of scarlet
  flames. Everything is brought to cinders in a matter of seconds.
Effect: Target All Foes in Range. Lethal. Projectile Move. Roll 3 Chance Dice to inflict
  2nd Degree Burn on those affected.
Name: Searing Shot
Power: 5
Target: All Foes
Type: Fire
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