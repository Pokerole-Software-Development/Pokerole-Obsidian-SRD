---
Accuracy1: Dexterity
Accuracy2: Channel/Nature
AddedEffects: {}
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: "A splash of sea water that literally adds more and more salt to the\
  \ foe\u2019s wounds."
Effect: Single Target. *Add 3 Extra Dice to the Damage Pool if the Target is at half
  HP or less.
Name: Brine
Power: 2
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