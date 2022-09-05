---
Accuracy1: Special
Accuracy2: Nature
Damage1: ''
Damage2: ''
Description: The user sends out a haze that disturbs all the Pokemon engaged in battle.
  It may conceal whoever is inside.
DmgType: Support
Effect: Remove all Increased or Reduced Attributes and Traits on everyone on the Battlefield.
Name: Haze
Power: 0
Target: Battlefield
Type: Ice
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