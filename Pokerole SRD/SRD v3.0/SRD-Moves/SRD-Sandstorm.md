---
Accuracy1: Special
Accuracy2: Nature
AddedEffects:
  TerrainEffect: Sandstorm
Attributes:
  Duration: 4
  WindMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: A fierce sandstorm starts raging all around the battlefield. Cover your
  eyes, nose and face! The rough sand will hurt you!
Effect: Target Battlefield. Wind Move. Activate Sandstorm Weather. Duration 4 Rounds.
Name: Sandstorm
Power: 0
Target: Battlefield
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