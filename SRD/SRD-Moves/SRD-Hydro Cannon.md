---
Accuracy1: Special
Accuracy2: Channel
Damage1: Special
Damage2: ''
Description: The Pokemon blasts the foe with a water surge that could bring down a
  house. The user needs to res afterwards.
DmgType: Special
Effect: Must Recharge. -1 Accuracy.
Name: Hydro Cannon
Power: 6
Target: Foe
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