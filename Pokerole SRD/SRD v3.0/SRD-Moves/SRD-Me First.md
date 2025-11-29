---
Accuracy1: Insight
Accuracy2: Athletic
AddedEffects: {}
Attributes:
  CopyMove: true
  Reaction: '1'
  Unique: true
Category: Support
Damage1: SameasCopiedMove+1
Damage2: ''
Description: The user anticipates the next Move the target will use and impatiently
  interrupts to be the first in line.
Effect: Single Target. Reaction 1. Copy Move. Support Moves can't be copied. Unique
  Moves can't be copied. You may choose another Target(s) for the copied Move.
Name: Me First
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