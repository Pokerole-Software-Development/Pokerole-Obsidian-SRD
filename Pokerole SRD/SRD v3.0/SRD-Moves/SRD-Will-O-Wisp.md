---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Burn
Attributes:
  AccuracyReduction: -2
Category: Support
Damage1: ''
Damage2: ''
Description: The user calls upon an eerie blue flame made with the souls of the departed.
  They appear harmless until they have you surrounded.
Effect: Single Target. Low Accuracy 2. Inflict 1st Degree Burn on the Target. Using
  this Move against the same Target increases the Burn Degree.
Name: Will-O-Wisp
Power: 0
Target: Foe
Type: Fire
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