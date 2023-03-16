---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Poison
Attributes:
  AccuracyReduction: 2
Category: Special
Damage1: Special
Damage2: ''
Description: The target is attacked with a discharge of filthy gases.
Effect: Roll 4 Chance Dice Poison the Foe. -2 Accuracy.
Name: Smog
Power: 1
Target: Foe
Type: Poison
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