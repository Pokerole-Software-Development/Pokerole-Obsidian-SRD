---
Accuracy1: Will
Accuracy2: Channel
Damage1: ''
Damage2: ''
Description: The user gets prepared to receive a fatal blow. It resists the pain despite
  being seriously hurt.
DmgType: Support
Effect: Priority 5. Shield Move. For the rest of the Round damaging moves can not
  reduce the user's HP to less then 1. Status Ailments, Weather Conditions, Recoil,
  Self inflicted damage can still deal damage.
Name: Endure
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