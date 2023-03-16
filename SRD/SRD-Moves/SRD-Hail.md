---
Accuracy1: Special
Accuracy2: Nature
AddedEffects:
  TerrainEffect: Hail
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The user summons a hailstorm that will stay on the battlefield for some
  time.
Effect: Hail Weather is activated for the next 4 Rounds.
Name: Hail
Power: 0
Target: Battlefield
Type: Ice
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