---
Accuracy1: Will
Accuracy2: Channel
Damage1: ''
Damage2: ''
Description: The user creates an energy shield to deflect a blow. Some Pokemon may
  even perform an amazing parry to block the incoming attack.
DmgType: Support
Effect: Priority 5. Shield. Reduce 3 Damage this pokemon would receive from a damaging
  move. Negate effects of Support Moves that target the user. Reduce to zero the set
  damage from a move the user would take.
Name: Protect
Power: 0
Target: User
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