---
Accuracy1: TOUGH
Accuracy2: PERFORM
Damage1: ''
Damage2: ''
Description: The Pokemon shakes its scales around, to sharpen, shed, and rearrange
  them. It's a bit rough, but in the end the Pokemon feels more focused for battle.
DmgType: SUPPORT
Effect: User deals Damage to itself equal to Half of its total HP rounded down. Increase
  User's Strength, Dexterity, Special, Defense and Sp. Defense.
Name: Clangorous Soul
Power: 0
Target: User
Type: Dragon
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