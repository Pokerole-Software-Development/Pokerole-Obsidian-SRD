---
Accuracy1: Insight
Accuracy2: Nature
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Paralyze
Attributes:
  AccuracyReduction: 1
Category: Support
Damage1: ''
Damage2: ''
Description: A tide of bright lightning streams from the floor onto the foe. The target's
  body will be cramped for hours.
Effect: Paralyze the foe. -1 Accuracy.
Name: Thunder Wave
Power: 0
Target: Foe
Type: Electric
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