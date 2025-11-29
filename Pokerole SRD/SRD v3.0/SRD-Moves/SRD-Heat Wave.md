---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 1
    Type: Burn
Attributes:
  AccuracyReduction: -1
  WindMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: A large wave of extra-hot air that can set fire to everything it touches.
Effect: Target All Foes in Range. Low Accuracy 1. Wind Move. Roll 1 Chance Die to
  inflict 1st Degree Burn on those affected.
Name: Heat Wave
Power: 3
Target: All Foes
Type: Fire
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