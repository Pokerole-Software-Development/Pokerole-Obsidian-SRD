---
Accuracy1: Special
Accuracy2: Perform
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Sleep
Attributes:
  AccuracyReduction: 3
  SoundBased: true
Category: Support
Damage1: ''
Damage2: ''
Description: The user plays a beautiful and soothing melody that lulls the target
  into a peaceful sleep.
Effect: Sound Based. Put the Target to Sleep. -3 Accuracy.
Name: Grass Whistle
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