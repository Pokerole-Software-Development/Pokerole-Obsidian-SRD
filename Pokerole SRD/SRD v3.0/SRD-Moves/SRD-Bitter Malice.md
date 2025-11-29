---
Accuracy1: Special
Accuracy2: Intimidate
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 3
    Type: Freeze
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: The victim is hit by an onslaught of evil energy. Filled with dread,
  the victim is unable to move.
Effect: Single Target. Roll 3 Chance Dice to Freeze the Foe. *If the Target already
  has an active Status Condition, add 2 Extra Dice to the Damage Pool of this Move.
Name: Bitter Malice
Power: 3
Target: Foe
Type: Ghost
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