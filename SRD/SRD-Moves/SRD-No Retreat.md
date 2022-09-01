---
Accuracy1: INSIGHT
Accuracy2: NATURE
Damage1: ''
Damage2: ''
Description: No surrender. No retreat. Until victory always.
DmgType: SUPPORT
Effect: Increase the User's Strength, Dexterity, Special, Defense and Sp. Defense.
  The user is now blocked.
Name: No Retreat
Power: 0
Target: User
Type: Fighting
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