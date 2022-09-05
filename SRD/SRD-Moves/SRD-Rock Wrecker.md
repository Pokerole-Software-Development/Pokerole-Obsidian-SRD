---
Accuracy1: Strength
Accuracy2: Channel
Damage1: Strength
Damage2: ''
Description: The user shoots a huge boulder as if it were a cannon ball that can even
  go through thick walls. This, however, requires a lot of energy from the user.
DmgType: Physical
Effect: Ranged. Must Recharge. Lethal. -1 Accuracy.
Name: Rock Wrecker
Power: 6
Target: Foe
Type: Rock
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