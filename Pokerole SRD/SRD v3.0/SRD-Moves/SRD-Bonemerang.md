---
Accuracy1: Strength
Accuracy2: Channel
AddedEffects: {}
Attributes:
  AccuracyReduction: -1
  DoubleAction: true
  PhysicalRanged: true
  Ranged: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon throws their bone against the foe, the bone spins in\
  \ the air and makes a comeback to strike a second time."
Effect: Single Target. Low Accuracy 1. Ranged. Double Action.
Name: Bonemerang
Power: 2
Target: Foe
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