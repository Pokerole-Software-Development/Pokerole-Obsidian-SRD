---
Accuracy1: Special
Accuracy2: Channel
Damage1: Special
Damage2: ''
Description: The user releases an addictive sweet-smelling steam, do not be fooled
  as it is toxic and has nasty side-effects.
DmgType: Special
Effect: Roll 2 Chance Dice to Confuse the Foe.
Name: Strange Steam
Power: 3
Target: Foe
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