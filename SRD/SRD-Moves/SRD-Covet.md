---
Accuracy1: Clever
Accuracy2: Stealth
Damage1: Strength
Damage2: ''
Description: The User approaches with caution, deals a quick strike and takes the
  chance to steal the target's item.
DmgType: Physical
Effect: If the user is not holding an item, Steal the target's Held Item.
Name: Covet
Power: 2
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