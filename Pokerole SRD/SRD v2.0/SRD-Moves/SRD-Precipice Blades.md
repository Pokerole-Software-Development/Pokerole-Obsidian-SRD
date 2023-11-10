---
Accuracy1: Strength
Accuracy2: Channel
AddedEffects: {}
Attributes:
  AccuracyReduction: 2
  Lethal: true
  PhysicalRanged: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: Giant blades emerge from the earth with every step of the user. If you
  fall into them, they are almost impossible to survive.
Effect: Lethal. Ranged. -2 Accuracy.
Name: Precipice Blades
Power: 5
Target: All Foes
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