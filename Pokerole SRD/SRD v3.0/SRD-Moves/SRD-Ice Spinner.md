---
Accuracy1: Dexterity/Strength
Accuracy2: Athletic
AddedEffects: {}
Attributes:
  ResetTerrain: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user covers their feet with sharp ice blades and skates through the
  field making gracious spins to hit the target. The battlefield ends up cut by the
  blades though.
Effect: Single Target. Remove any active Terrain on the Battlefield.
Name: Ice Spinner
Power: 3
Target: Foe
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