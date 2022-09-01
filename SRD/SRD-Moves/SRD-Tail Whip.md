---
Accuracy1: CUTE
Accuracy2: PERFORM
Damage1: ''
Damage2: ''
Description: The Pokemon moves its tail in such a cute way that the foe will easily
  let its guard down.
DmgType: SUPPORT
Effect: Reduce the foe's Defense.
Name: Tail Whip
Power: 0
Target: All Foes
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