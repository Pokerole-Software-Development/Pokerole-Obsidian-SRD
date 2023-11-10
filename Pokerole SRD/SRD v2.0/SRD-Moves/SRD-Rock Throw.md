---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  AccuracyReduction: 1
  PhysicalRanged: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user picks up a rock or pebble and throws it at the foe.
Effect: Ranged. -1 Accuracy.
Name: Rock Throw
Power: 2
Target: Foe
Type: Rock
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