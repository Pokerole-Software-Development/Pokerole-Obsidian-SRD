---
Accuracy1: Tough
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Confuse
Attributes:
  AccuracyReduction: 3
Category: Support
Damage1: ''
Damage2: ''
Description: The Pokemon emits a series of ultrasonic waves that make the foe dizzy
  and disoriented.
Effect: Confuse the foe. -3 Accuracy.
Name: Supersonic
Power: 0
Target: Foe
Type: Normal
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