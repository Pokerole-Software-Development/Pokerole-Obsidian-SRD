---
Accuracy1: Special
Accuracy2: Nature
AddedEffects: {}
Attributes:
  AccuracyReduction: -1
  MustRecharge: true
Category: Special
Damage1: Special
Damage2: ''
Description: The user roots down and calls upon the force of nature. Thorny roots
  and plants grow in a frenzy around the foe. This display of power leaves the user
  quite exhausted.
Effect: Single Target. Low Accuracy 1. Must Recharge.
Name: Frenzy Plant
Power: 6
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