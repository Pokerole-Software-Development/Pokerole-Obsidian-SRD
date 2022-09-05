---
Accuracy1: Insight
Accuracy2: Nature
Damage1: ''
Damage2: ''
Description: A tide of bright lightning streams from the floor onto the foe. The target's
  body will be cramped for hours.
DmgType: Support
Effect: Paralyze the foe. -1 Accuracy.
Name: Thunder Wave
Power: 0
Target: Foe
Type: Electric
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