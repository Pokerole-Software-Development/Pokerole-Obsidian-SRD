---
Accuracy1: DEXTERITY
Accuracy2: PERFORM
Damage1: ''
Damage2: ''
Description: The user starts dancing around with wobbly movements. Friends and foes
  will get dizzy by trying to follow it.
DmgType: SUPPORT
Effect: Inflicts Confusion.
Name: Teeter Dance
Power: 0
Target: Area
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