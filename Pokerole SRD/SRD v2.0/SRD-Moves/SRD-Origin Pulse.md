---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  AccuracyReduction: 2
  Lethal: true
Category: Special
Damage1: Special
Damage2: ''
Description: The Pokemon sends a giant pulse underwater that creates a chain reaction
  and causes water to move in large streams. It is believed that all water in the
  sea moves thanks to this.
Effect: Lethal. -2 Accuracy.
Name: Origin Pulse
Power: 4
Target: Foe
Type: Water
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