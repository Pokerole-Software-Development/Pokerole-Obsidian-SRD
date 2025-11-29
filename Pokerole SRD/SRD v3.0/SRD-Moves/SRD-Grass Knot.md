---
Accuracy1: Dexterity
Accuracy2: Nature
AddedEffects: {}
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: "The user snares the foe\u2019s feet with a grass tangle to make it fall\
  \ into the ground. The bigger they are, the harder they fall."
Effect: Single Target. *Add 1 Extra Damage Dice for every 50kg of weight on the foe,
  up to 4 Dice may be added this way.
Name: Grass Knot
Power: 1
Target: Foe
Type: Grass
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