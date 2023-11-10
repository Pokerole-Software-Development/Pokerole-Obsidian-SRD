---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Recoil: true
Category: Special
Damage1: Special
Damage2: ''
Description: A concentrated ray of light that is capable of melting even the thickest
  steel plates. Unfortunately the user will also have trouble handling this power.
Effect: Recoil.
Name: Steel Beam
Power: 6
Target: Foe
Type: Steel
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