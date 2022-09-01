---
Accuracy1: DEXTERITY
Accuracy2: ATHLETIC
Damage1: ''
Damage2: ''
Description: The user cuts down the rough edges of its body to make it as sharp as
  a razor.
DmgType: SUPPORT
Effect: Increase the User's Strength.
Name: Sharpen
Power: 0
Target: User
Type: Normal
---

#PokeroleSRD/Moves

## `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`