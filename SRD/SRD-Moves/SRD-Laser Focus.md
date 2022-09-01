---
Accuracy1: INSIGHT
Accuracy2: ALERT
Damage1: ''
Damage2: ''
Description: Through its incredible awareness the Pokemon finds a straight path into
  a weak point of the foe. The attack that follows is usually devastating.
DmgType: SUPPORT
Effect: The next time the user lands a hit it will be treated as if it were a Critical
  Hit.
Name: Laser Focus
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