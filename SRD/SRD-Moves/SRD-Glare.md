---
Accuracy1: Tough
Accuracy2: Intimidate
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Paralyze
Attributes:
  AccuracyReduction: 1
Category: Support
Damage1: ''
Damage2: ''
Description: The Pokemon uses its intimidating glare to paralyze the foe with sheer
  terror.
Effect: Paralyze the foe. -1 Accuracy.
Name: Glare
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