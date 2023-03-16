---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 3
    Type: Confuse
Attributes:
  AccuracyReduction: 2
  Lethal: true
Category: Special
Damage1: Special
Damage2: ''
Description: The user attacks by wrapping the opponent in a fierce wind that carries
  the target up into the sky.
Effect: Lethal. Roll 3 Chance Dice to Confuse the Foe. If Rain Weather in effect ignore
  this moves reduced accuracy. -2 Accuracy.
Name: Hurricane
Power: 5
Target: Foe
Type: Flying
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