---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: Targets
    ChanceDice: 3
    Stages: -1
    Stats:
    - Accuracy
Attributes:
  AccuracyReduction: -2
Category: Special
Damage1: Special
Damage2: ''
Description: "When you can\u2019t see what creatures lurk inside the water, that\u2019\
  s when you know they are the ones that went fishing."
Effect: Target All Foes in Range. Low Accuracy 2. Roll 3 Chance Dice to Reduce 1 success
  to all the Accuracy Rolls of those affected.
Name: Muddy Water
Power: 3
Target: All Foes
Type: Water
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