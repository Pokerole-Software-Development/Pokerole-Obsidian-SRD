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
Description: The user shakes the tectonic plates underneath the battlefield, trying
  to find a fault, when they do, this Move is devastating.
Effect: Area Move. Ranged. Before you roll damage, Roll 1 die to determine this Move's
  Power. If the Target is out of range due to using the Move "Dig" this Move hits
  anyways.
Name: Magnitude
Power: X
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