---
Accuracy1: Strength
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Ranged: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: ''
Effect: Single Target. Ranged. Roll 3 Chance Dice to Flinch the Foe.
Name: Mountain Gale
Power: 4
Target: Foe
Type: Ice
---

#PokeroleSRD/Moves

### `= this.name`
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Category          | Power          |
| ------------- | --------------- | ----------------  | -------------- |
| `= this.Type` | `= this.Target` | `= this.Category` | `= this.Power` | 

**Effect:** `= this.Effect`