---
Accuracy1: Special
Accuracy2: Nature
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Paralyze
Attributes:
  AccuracyReduction: 2
Category: Support
Damage1: ''
Damage2: ''
Description: A blow of dust that paralyzes the target on the spot and cramps its muscles.
Effect: Paralyze the Foe. -2 Accuracy.
Name: Stun Spore
Power: 0
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