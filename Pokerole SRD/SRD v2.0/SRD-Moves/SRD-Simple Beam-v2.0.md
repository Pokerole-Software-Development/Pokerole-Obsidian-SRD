---
Accuracy1: Insight
Accuracy2: Empathy
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: SimpleBeam
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The Pokemon sends a small psychic wave to its target, giving it a simpler
  point of view about the world.
Effect: Target Pokemon ability is now "Simple".
Name: Simple Beam
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