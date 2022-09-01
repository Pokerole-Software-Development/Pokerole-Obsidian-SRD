---
Accuracy1: ''
Accuracy2: ''
Damage1: ''
Damage2: ''
Description: ''
DmgType: SUPPORT
Effect: The user will provide cover to the target from Ranged attacks and is more
  likely to be hit by close-range attacks. The level of Cover the user provides will
  depend on its size.
Name: Cover An Ally
Power: 0
Target: One Ally
Type: Typeless
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