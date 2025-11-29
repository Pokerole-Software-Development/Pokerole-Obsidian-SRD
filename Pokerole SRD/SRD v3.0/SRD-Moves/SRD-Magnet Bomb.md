---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  NeverMiss: true
  PhysicalRanged: true
  ProjectileMove: true
  Ranged: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user lights the fuse of a magnetized bomb. Guess who is the other
  magnet?
Effect: Single Target. Ranged. Never Miss. Projectile Move.
Name: Magnet Bomb
Power: 2
Target: Foe
Type: Steel
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