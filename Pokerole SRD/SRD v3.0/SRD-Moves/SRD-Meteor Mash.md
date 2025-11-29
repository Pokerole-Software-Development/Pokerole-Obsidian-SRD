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
  AccuracyReduction: -1
  FistMove: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "A great meteor fell, leading to the extinction of all prehistoric Pok\xE9\
  mon. The user re-enacts that meteor on a smaller scale, as it only needs to extinguish\
  \ one."
Effect: Single Target. Low Accuracy 1. Fist Move. Roll 2 Chance Dice to increase the
  User's Strength by 1.
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