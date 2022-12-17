---
Accuracy1: Vitality
Accuracy2: Brawl
AddedEffects: {}
Attributes: {}
Damage1: Strength
Damage2: ''
Description: The Pokemon becomes a giant energy shield that tramples everything in
  its wake. If the foe is under the effects of the Dynamax phenomenon all its energy
  will be swept away.
DmgType: Physical
Effect: If the Foe is under the effects of Dynamax, This Move becomes Lethal and you
  add 4 Extra Dice to the Damage Pool.
Name: Behemoth Bash
Power: 4
Target: Foe
Type: Steel
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