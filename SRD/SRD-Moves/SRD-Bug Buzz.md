---
Accuracy1: SPECIAL
Accuracy2: PERFORM
Damage1: SPECIAL
Damage2: ''
Description: The Pokemon uses its wings or part of its body to emit sound waves that
  harm and affect the target.
DmgType: SPECIAL
Effect: Sound Based. Roll 1 Chance Dice to reduce foe's Sp. Defense.
Name: Bug Buzz
Power: 3
Target: Foe
Type: Bug
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