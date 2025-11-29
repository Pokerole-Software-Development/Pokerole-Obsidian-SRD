---
Accuracy1: Special
Accuracy2: Nature
AddedEffects:
  Ailments:
  - Affects: Targets
    ChanceDice: 3
    Type: Freeze
Attributes:
  AccuracyReduction: 2
  Lethal: true
  WindMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: "A furious storm ravages the battlefield, cold winds swirl in such a\
  \ menacing way that you don\u2019t know if the chill comes from the ice or the sheer\
  \ terror invading you."
Effect: Area Move. Low Accuracy 2. Lethal. Wind Move. Roll 3 Chance Dice to Freeze
  those affected.
Name: Bleakwind Storm
Power: 4
Target: Area
Type: Flying
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