---
Accuracy1: Special
Accuracy2: Channel
Damage1: ''
Damage2: ''
Description: With a disgusting diet and training, the user learns how to turn its
  fluids into a deadly toxin.
DmgType: Support
Effect: Badly Poison the Foe. -1 Accuracy.
Name: Toxic
Power: 0
Target: Foe
Type: Poison
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