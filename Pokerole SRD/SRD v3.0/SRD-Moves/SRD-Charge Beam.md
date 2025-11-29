---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: User
    ChanceDice: 5
    Stages: 1
    Stats:
    - Special
Attributes:
  AccuracyReduction: -1
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon releases an electric beam, if any charge remains unused,\
  \ it will make use of it to boost its power."
Effect: Single Target. Low Accuracy 1. Roll 5 Chance Dice to Increase User's Special
  by 1.
Name: Charge Beam
Power: 2
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