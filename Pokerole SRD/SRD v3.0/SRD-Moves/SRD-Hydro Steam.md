---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: "When water and fire work together you\u2019ll wish they didn\u2019t\
  \ set aside their differences."
Effect: Single Target. Roll 3 Chance Dice to inflict 1st Degree Burn on the Target.
  *If Sunny Weather is active, this Move does not reduce damage due to it, and has
  2 Extra Dice to the Damage pool of this Move.
Name: Hydro Steam
Power: 3
Target: Foe
Type: Water
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