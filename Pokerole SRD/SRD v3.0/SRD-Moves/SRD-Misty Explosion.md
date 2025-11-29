---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Lethal: true
  UserFaints: true
Category: Special
Damage1: Special
Damage2: ''
Description: The user razes the field with a searing nuke of made of love, joy, kisses,
  and pink glitter. It is deadly.
Effect: Area Attack. Lethal. The User faints after using this Move. *If Misty Terrain
  is active, add 4 Extra Dice to the Damage Pool of this Move.
Name: Misty Explosion
Power: 6
Target: Area
Type: Fairy
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