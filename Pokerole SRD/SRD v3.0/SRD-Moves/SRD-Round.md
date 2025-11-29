---
Accuracy1: Special
Accuracy2: Perform
AddedEffects: {}
Attributes:
  SoundMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: The user attacks the foe with the power of music, if another one joins
  the performance, the musical harmony will rock their public!
Effect: Single Target. Sound Move. *If the user and an ally are able to use Round.
  Both may choose to do it at the same time. If they do, add 3 Extra Dice to the Damage
  Pool of both Pokemon.
Name: Round
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