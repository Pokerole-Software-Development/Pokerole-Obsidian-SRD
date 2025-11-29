---
Accuracy1: Special
Accuracy2: Nature
AddedEffects: {}
Attributes:
  ProjectileMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon creates a puff of pollen that explodes on the foe's face\
  \ and gives them a terrible allergy. When consumed, these puffs are sweet and very\
  \ nutritious."
Effect: Single Target. Projectile Move. * Or target One Ally. *When this move is used
  against an ally, it will heal 2 HP instead of damage, Spend 1 Will Point to get
  this effect.
Name: Pollen Puff
Power: 3
Target: Ally
Type: Bug
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