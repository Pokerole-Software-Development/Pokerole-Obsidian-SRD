---
Accuracy1: Insight
Accuracy2: Channel
Damage1: ''
Damage2: ''
Description: The user reads the foe's mind. It knows exactly what to do next.
DmgType: Support
Effect: This Pokemon gets 2 automatic successes on the next Accuracy Roll or Evasion
  Roll against the target.
Name: Mind Reader
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