---
Accuracy1: CLEVER
Accuracy2: MEDICINE
Damage1: ''
Damage2: ''
Description: ''
DmgType: SUPPORT
Effect: The User applies CPR and/or first aid to an unconcious Ally. Target won't
  receive Lethal Damage each hour anymore. Each Lethal Damage on the Ally reduces
  1 Success to the Accuracy Pool of this Maneuver.
Name: Stabilize An Ally
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