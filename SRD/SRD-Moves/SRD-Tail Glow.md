---
Accuracy1: Insight
Accuracy2: Nature
Damage1: ''
Damage2: ''
Description: The user emits a strong light. This Pokemon will stare at its brightness
  to enter a trance.
DmgType: Support
Effect: Increase the User's Special by 3.
Name: Tail Glow
Power: 0
Target: User
Type: Bug
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