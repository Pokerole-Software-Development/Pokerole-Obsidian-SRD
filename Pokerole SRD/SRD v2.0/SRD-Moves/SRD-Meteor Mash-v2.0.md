---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  StatChanges:
  - Affects: User
    ChanceDice: 2
    Stages: 1
    Stats:
    - Strength
Attributes:
  AccuracyReduction: 1
  FistBased: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user charges with a strong fist and strikes like a meteor.
Effect: Fist Based. Roll 2 Chance Dice to Increase the User's Strength. -1 Accuracy.
Name: Meteor Mash
Power: 3
Target: Foe
Type: Steel
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