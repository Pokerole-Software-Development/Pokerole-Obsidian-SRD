---
Accuracy1: Beauty
Accuracy2: Nature
Damage1: ''
Damage2: ''
Description: Using some frosting the Pokemon decorates their target to look bigger,
  more powerful, and incredibly delicious!
DmgType: Support
Effect: Increase the Strength and Special of One Ally by 2
Name: Decorate
Power: 0
Target: One Ally
Type: Fairy
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