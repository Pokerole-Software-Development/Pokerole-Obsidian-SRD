---
Accuracy1: Tough
Accuracy2: Intimidate
Damage1: ''
Damage2: ''
Description: The Pokemon curls up its body. In a calm but menacing position it prepares
  to deliver its strike.
DmgType: Support
Effect: Increase the User's Strength, Defense, and Accuracy.
Name: Coil
Power: 0
Target: User
Type: Poison
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