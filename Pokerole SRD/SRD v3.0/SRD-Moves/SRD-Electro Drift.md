---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Lethal: true
  Unique: true
Category: Special
Damage1: Special
Damage2: ''
Description: Miraidon accelerates its turbines and races forward at ultrafast speeds,
  piercing its target in a blast of futuristic electricity
Effect: Single Target. Lethal. Unique. *Add 4 Extra Dice to the Damage pool of this
  Move if the Target is weak to Electric-Type Moves.
Name: Electro Drift
Power: 4
Target: Foe
Type: Electric
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