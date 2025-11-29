---
Accuracy1: Clever
Accuracy2: Nature
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Poison
Attributes:
  AccuracyReduction: -2
  PowderMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: "A cloud of noxius powder that immediately sends the target\u2019s immune\
  \ system into overdrive."
Effect: Single Target. Low Accuracy 3. Powder Move. Poison the Target.
Name: Poison Powder
Power: 0
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