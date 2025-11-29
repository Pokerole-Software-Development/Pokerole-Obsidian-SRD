---
Accuracy1: Special
Accuracy2: Nature
AddedEffects:
  TerrainEffect: MudSport
Attributes:
  Duration: 4
Category: Support
Damage1: ''
Damage2: ''
Description: "The user covers the whole field with mud. Electricity can\u2019t flow\
  \ properly, so Electric attacks will be severely impaired."
Effect: Target Battlefield. Physical & Special Electric-Type Moves have Power 0. Pokemon
  weak to Electric-Type Moves won't receive Super-Effective Damage from them. Duration
  4 Rounds.
Name: Mud Sport
Power: 0
Target: Battlefield
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