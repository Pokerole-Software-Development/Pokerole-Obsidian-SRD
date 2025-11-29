---
Accuracy1: Special
Accuracy2: Nature
AddedEffects: {}
Attributes:
  Duration: 4
Category: Support
Damage1: ''
Damage2: ''
Description: "A single drop of water can\u2019t put off a raging fire, but what is\
  \ the ocean but a collection of drops."
Effect: Target Battlefield. Physical & Special Fire-Type Moves have Power 0. Pokemon
  weak to Fire-Type Moves won't receive Super-Effective Damage from them. Duration
  4 Rounds.
Name: Water Sport
Power: 0
Target: Battlefield
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