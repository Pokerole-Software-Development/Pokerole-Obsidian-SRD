---
Accuracy1: Special
Accuracy2: Channel
Damage1: ''
Damage2: ''
Description: The Pokemon appears to change its own physiology. This effect changes
  the Type of the user to match another Pokemon in sight.
DmgType: Support
Effect: The Pokemon is now the same type of one of its foes. Lasts for a Scene or
  until this move is used again.
Name: Reflect Type
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