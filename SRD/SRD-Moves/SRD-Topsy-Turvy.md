---
Accuracy1: TOUGH
Accuracy2: INTIMIDATE
Damage1: ''
Damage2: ''
Description: The user changes the nature of its target, bad things become good and
  good things become bad.
DmgType: SUPPORT
Effect: Any Decreases on the foe's Attributes become Increases and vice versa.
Name: Topsy-Turvy
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