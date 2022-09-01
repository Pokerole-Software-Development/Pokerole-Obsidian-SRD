---
Accuracy1: SPECIAL
Accuracy2: NATURE
Damage1: ''
Damage2: ''
Description: The user coats itself in a ring of special flowing water that lessens
  the pain.
DmgType: SUPPORT
Effect: If successful spent 1 Will point to activate. At the end of each Round, recover
  1 HP. Lasts 4 Rounds.
Name: Aqua Ring
Power: 0
Target: User
Type: Water
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