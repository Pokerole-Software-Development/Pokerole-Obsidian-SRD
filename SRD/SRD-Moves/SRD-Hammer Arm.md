---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: -1
    Stats:
    - Dexterity
Attributes:
  AccuracyReduction: 1
Category: Physical
Damage1: Strength
Damage2: ''
Description: A mighty arm thrust that leaves the user quite tired.
Effect: After dealing damage, Reduce user's Dexterity. -1 Accuracy.
Name: Hammer Arm
Power: 4
Target: Foe
Type: Fighting
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