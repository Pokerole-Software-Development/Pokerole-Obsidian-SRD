---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes: {}
Damage1: ''
Damage2: ''
Description: The user soaks the battlefield with moisture, making it harder for fire
  attacks to ignite.
DmgType: Support
Effect: For the next 4 Rounds Fire Type attacks won't add their Power to the Damage
  Pool.
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

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`