---
Accuracy1: Special
Accuracy2: Nature
AddedEffects:
  TerrainEffect: Sunny
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The Pokemon will raise the temperature along with the sun, it doesn't
  work at night, indoors, underground, or underwater.
Effect: Sunny Weather is activated for the next 4 Rounds.
Name: Sunny Day
Power: 0
Target: Battlefield
Type: Fire
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