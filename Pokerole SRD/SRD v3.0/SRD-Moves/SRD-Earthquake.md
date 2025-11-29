---
Accuracy1: Strength
Accuracy2: Nature
AddedEffects: {}
Attributes:
  PhysicalRanged: true
  Ranged: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user calls the forces of nature. The earth shakes violently and everything
  crumbles to the ground.
Effect: Area Move. Ranged. If the Target is out of range due to using the Move "Dig"
  this Move hits anyways.
Name: Earthquake
Power: 4
Target: Area
Type: Ground
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