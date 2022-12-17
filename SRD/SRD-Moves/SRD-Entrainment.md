---
Accuracy1: Cool
Accuracy2: Perform
AddedEffects: {}
Attributes: {}
Damage1: ''
Damage2: ''
Description: The Pokemon dances with a catchy rhythm. The target starts dancing too
  and both connect to a very personal level through this performance.
DmgType: Support
Effect: The target's Ability is replaced by the User's own Ability. (ie. Luvdiscs's
  Swift Swim Ability will replace Geodude's Sturdy Ability).
Name: Entrainment
Power: 0
Target: Foe
Type: Normal
---

#PokeroleSRD/Moves

### `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`