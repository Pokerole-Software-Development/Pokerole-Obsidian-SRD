---
Accuracy1: DEXTERITY
Accuracy2: PERFORM
Damage1: ''
Damage2: ''
Description: The Pokemon assists an ally. Together they are stronger.
DmgType: SUPPORT
Effect: Target Pokemon gets 2 Extra Dice on its next Skill, Accuracy and Damage Rolls.
  Priority 5.
Name: Helping Hand
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