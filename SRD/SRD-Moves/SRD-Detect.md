---
Accuracy1: Insight
Accuracy2: Alert
AddedEffects: {}
Attributes:
  ShieldMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: The user detects the intentions of the attacker and acts out to minimize
  the damage.
Effect: Priority. Shield Move. Reduce 3 Damage this pokemon would receive from a Damaging
  Move. Negate effects of Support Moves that target the user. Reduce to zero the set
  damage from a move the user would take.
Name: Detect
Power: 0
Target: User
Type: Fighting
---

#PokeroleSRD/Moves

### `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Category          | Power          |
| ------------- | --------------- | ----------------  | -------------- |
| `= this.Type` | `= this.Target` | `= this.Category` | `= this.Power` | 

**Effect:** `= this.Effect`