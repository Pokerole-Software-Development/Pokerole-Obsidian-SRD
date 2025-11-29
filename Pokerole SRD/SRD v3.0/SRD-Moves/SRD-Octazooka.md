---
Accuracy1: Insight
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: Targets
    ChanceDice: 5
    Stages: -1
    Stats:
    - Accuracy
Attributes:
  AccuracyReduction: -2
  ProjectileMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: "A jet of black ink shot straight into the foe\u2019s eyes. This Move\
  \ is hard to aim but returns the favor."
Effect: Single Target. Low Accuracy 2. Projectile Move. Roll 5 Chance Dice to Reduce
  1 success to all Accuracy Rolls of the foe.
Name: Octazooka
Power: 2
Target: Foe
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