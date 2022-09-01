---
Accuracy1: INSIGHT
Accuracy2: NATURE
Damage1: ''
Damage2: ''
Description: The user concentrates all the electricity in its body to be released.
DmgType: SUPPORT
Effect: Add 2 Dice to the Damage Pool to the next Electric Damaging move the user
  performs.
Name: Charge
Power: 0
Target: User
Type: Electric
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