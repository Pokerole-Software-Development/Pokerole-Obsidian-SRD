---
Accuracy1: Special
Accuracy2: Channel
Damage1: ''
Damage2: ''
Description: The user shoots a stream of water and moisture that clings to the foe's
  body as an overcoat.
DmgType: Support
Effect: Change the target's Type to Water.
Name: Soak
Power: 0
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