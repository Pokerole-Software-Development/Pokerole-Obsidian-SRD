---
Accuracy1: CLEVER
Accuracy2: PERFORM
Damage1: ''
Damage2: ''
Description: The Pokemon hurriedly remembers one action performed by a partner. Some
  Pokemon can even do what a human does and assist him with any tasks.
DmgType: SUPPORT
Effect: Choose one Move known by a random member of your party. You performed that
  Move using the Accuracy roll from Assist.
Name: Assist
Power: 0
Target: One Ally
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