---
Accuracy1: Special
Accuracy2: Perform
AddedEffects: {}
Attributes:
  AccuracyReduction: -1
Category: Special
Damage1: Special
Damage2: ''
Description: "The user touches its foe while saying \u201CFreeze!\u201D, surprisingly,\
  \ the foe becomes frozen on a block of ice that melts as soon as the foe realizes\
  \ it was just a game."
Effect: Single Target. Low Accuracy 1. Remove all Increased or Reduced Attributes
  and Traits the Target may have. If the user of this Move is at its Final Stage of
  Evolution, this move fails.
Name: Freezy Frost
Power: 3
Target: Foe
Type: Ice
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