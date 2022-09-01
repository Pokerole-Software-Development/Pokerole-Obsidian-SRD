---
Accuracy1: VITALITY
Accuracy2: CHANNEL
Damage1: ''
Damage2: ''
Description: The Pokemon hardens its body surface as if it was made from the strongest
  iron around.
DmgType: SUPPORT
Effect: Increase the User's Defense by 2.
Name: Iron Defense
Power: 0
Target: User
Type: Steel
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