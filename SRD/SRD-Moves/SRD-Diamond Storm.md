---
Accuracy1: DEXTERITY
Accuracy2: CHANNEL
Damage1: STRENGTH
Damage2: ''
Description: The Pokemon summons a storm of diamonds over the field, these diamonds
  also serve as barriers the user can take cover into.
DmgType: PHYSICAL
Effect: Ranged. Roll 5 Chance Dice to Increase the User's Defense by 2.
Name: Diamond Storm
Power: 4
Target: All Foes
Type: Rock
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