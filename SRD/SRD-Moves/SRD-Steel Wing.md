---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  StatChanges:
  - Affects: User
    ChanceDice: 1
    Stages: 1
    Stats:
    - Def
Attributes:
  AccuracyReduction: 1
Category: Physical
Damage1: Strength
Damage2: ''
Description: The Pokemon uses its sharp feathers as if they were razors.
Effect: Roll 1 Chance Dice to Increase the User's Defense. -1 Accuracy.
Name: Steel Wing
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