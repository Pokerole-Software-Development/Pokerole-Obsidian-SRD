---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  AccuracyReduction: -2
  Lethal: true
  Unique: true
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon sends a giant pulse underwater that creates a chain reaction\
  \ in the tides, creating a series of tsunami waves. Not even water-pokemon can surf\
  \ through these wild currents."
Effect: Target All Foes in Range. Low Accuracy 2. Lethal. Unique. Ignore the Target's
  immunity to Water-Type Damage. If a Target is "Out of Range" due to using a Move,
  this Move hits anyways.
Name: Origin Pulse
Power: 5
Target: All Foes
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