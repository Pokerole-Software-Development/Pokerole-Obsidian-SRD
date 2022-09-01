---
Accuracy1: TOUGH
Accuracy2: INTIMIDATE
Damage1: ''
Damage2: ''
Description: The user mocks and teases the target to make it attack in a raging fury.
DmgType: SUPPORT
Effect: The target Pokemon can only perform Damaging Moves and Evasion actions for
  the next 4 Rounds.
Name: Taunt
Power: 0
Target: Foe
Type: Dark
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