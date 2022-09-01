---
Accuracy1: COOL
Accuracy2: ALLURE
Damage1: ''
Damage2: ''
Description: The user starts flattering and admiring its opponent. It sure makes it
  feel good about itself, but why?
DmgType: SUPPORT
Effect: Increase the foe's Special. Confuse foe.
Name: Flatter
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