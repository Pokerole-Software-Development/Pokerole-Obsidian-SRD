---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: Targets
    ChanceDice: 5
    Stages: -1
    Stats:
    - Accuracy
Attributes:
  AccuracyReduction: -1
Category: Special
Damage1: Special
Damage2: ''
Description: A cluster of leaves and twigs swirls around the foe, getting in its eyes
  and making it difficult to aim properly
Effect: Single Target. Low Accuracy 1. Roll 5 Chance Dice to Reduce 1 Success from
  all Accuracy Rolls of the foe.
Name: Leaf Tornado
Power: 2
Target: Foe
Type: Grass
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