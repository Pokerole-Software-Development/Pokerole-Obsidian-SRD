---
Accuracy1: Special
Accuracy2: Nature
AddedEffects: {}
Attributes:
  ProjectileMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: "A ball created out of the forces of the weather. Today\u2019s forecast\
  \ is cloudy with a chance of pain!"
Effect: Single Target. Projectile Move. *If there is a weather condition on the field,
  add 2 Extra Dice to the Damage Pool. This Move's type will change according to the
  Weather. Sun/Fire, Rain/Water, Hail or Snow/Ice, Sand/Rock, Wind/Flying.
Name: Weather Ball
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