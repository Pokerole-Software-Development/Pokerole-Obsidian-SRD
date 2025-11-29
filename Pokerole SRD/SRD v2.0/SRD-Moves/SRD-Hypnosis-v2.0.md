---
Accuracy1: Insight
Accuracy2: Allure
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Sleep
Attributes:
  AccuracyReduction: 4
Category: Support
Damage1: ''
Damage2: ''
Description: Employ a hypnotic suggestion to make the target feel drowsy and fall
  into a deep slumber. Works better on a target that is not in danger.
Effect: Put the target to sleep. Dark-Type Pokemon are affected by this move. -4 Accuracy.
Name: Hypnosis
Power: 0
Target: Foe
Type: Psychic
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