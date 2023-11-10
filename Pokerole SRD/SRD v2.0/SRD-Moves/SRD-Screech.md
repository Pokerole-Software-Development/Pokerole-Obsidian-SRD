---
Accuracy1: Tough
Accuracy2: Perform
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -2
    Stats:
    - Def
Attributes:
  SoundBased: true
Category: Support
Damage1: ''
Damage2: ''
Description: The user disrupts the fighting stance of its foe by sending a sharp sound
  to the foe's ears.
Effect: Reduce the foe's Defense by 2. Sound Based.
Name: Screech
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