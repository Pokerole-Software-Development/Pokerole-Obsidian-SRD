---
Accuracy1: CUTE
Accuracy2: ALLURE
Damage1: ''
Damage2: ''
Description: The user approaches its foe and gives it a lovely present that may be
  nice or may be a prank.
DmgType: PHYSICAL
Effect: Roll dice with a 50-50 chance of dealing 2 set damage to the target or recovering
  2 HP to the target. -1 Accuracy.
Name: Present
Power: 0
Target: Foe
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