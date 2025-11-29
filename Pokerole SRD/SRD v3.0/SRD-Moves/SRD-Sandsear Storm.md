---
Accuracy1: Special
Accuracy2: Nature
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 3
    Type: Burn2
Attributes:
  AccuracyReduction: -2
  Lethal: true
  WindMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: An overwhelming storm made of blistering sands rages through the battlefield,
  survivors describe it as being hit with live coal embers.
Effect: Area Move. Low Accuracy 2. Lethal. Wind Move. Roll 3 Chance Dice to inflict
  2nd Degree Burn on those affected.
Name: Sandsear Storm
Power: 4
Target: Area
Type: Ground
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