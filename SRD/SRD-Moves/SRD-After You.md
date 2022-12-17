---
Accuracy1: Cool
Accuracy2: Etiquette
AddedEffects: {}
Attributes: {}
Damage1: ''
Damage2: ''
Description: The user bows and courteously lets an ally or foe use their action first.
DmgType: Support
Effect: The Target will go first in the order of Initiative. Lasts for the rest of
  this Battle.
Name: After You
Power: 0
Target: One Ally
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