---
Accuracy1: INSIGHT
Accuracy2: ALERT
Damage1: ''
Damage2: ''
Description: The Pokemon uses its developed senses and mental ability to foresee the
  immediate future.
DmgType: SUPPORT
Effect: The Foe cannot evade moves performed by the user. User's Normal and Fighting
  Moves can affect Ghost Types and Ghost Moves can affect Normal Types.
Name: Foresight
Power: 0
Target: Foe
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