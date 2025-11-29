---
Accuracy1: Special
Accuracy2: Nature
AddedEffects:
  TerrainEffect: Hail
Attributes:
  Duration: 4
Category: Support
Damage1: ''
Damage2: ''
Description: A heavy snowstorm sweeps through the battlefield, covering everything
  with a thick layer of snow.
Effect: Target Battlefield. Activate Snowy Weather. Duration 4 Rounds.
Name: Snowscape
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