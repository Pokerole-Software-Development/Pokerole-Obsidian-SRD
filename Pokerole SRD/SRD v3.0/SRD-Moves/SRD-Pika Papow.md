---
Accuracy1: Cool
Accuracy2: Channel
AddedEffects: {}
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: The User lets out its energy in the form of a lightning strike, the happier
  the user feels the more energized it will be.
Effect: Single Target. *Add 1 Extra Die to the Damage Pool of this Move for every
  point of Happiness on the User. Up to 5 Dice may be added this way. If the user
  of this Move is at its Final Stage of Evolution, this move fails.
Name: Pika Papow
Power: 1
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