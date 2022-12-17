---
Accuracy1: Dexterity
Accuracy2: Channel
Damage1: Special
Damage2: ''
Description: ''
DmgType: Special
Effect: The most basic attack. Same move as "Struggle (Physical)", the user should
  use the one with highest stat (Strength/Special).
Name: Struggle (Special)
Power: 0
Target: Foe
Type: Typeless
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