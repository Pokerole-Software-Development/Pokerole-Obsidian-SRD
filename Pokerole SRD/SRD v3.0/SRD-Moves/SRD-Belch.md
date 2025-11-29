---
Accuracy1: MissingBeautyPoints
Accuracy2: ''
AddedEffects: {}
Attributes:
  AccuracyReduction: -1
  SoundMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: The user shoots a blast of venomous pins that inject venom into the foe,
  this venom is specially potent against those already compromised.
Effect: Single Target. Low Accuracy 1. Sound Move. The user must eat a berry or something
  similar during the Round before using this Move, otherwise it will fail. This effect
  only works once per berry/food eaten.
Name: Belch
Power: 4
Target: Foe
Type: Poison
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