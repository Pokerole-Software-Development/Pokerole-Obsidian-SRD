---
Accuracy1: Special
Accuracy2: Channel
Damage1: Special
Damage2: ''
Description: The Pokemon commands a tremendous lightning to strike a specific point
  on the ground. It's quite dangerous.
DmgType: Special
Effect: Lethal. Roll 3 Chance Dice to Paralyze foe. If performed under Sunny Weather,
  Accuracy becomes -3 instead. If performed under Rain Weather, Ignore this Moves
  Reduced Accuracy. -2 Accuracy.
Name: Thunder
Power: 5
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