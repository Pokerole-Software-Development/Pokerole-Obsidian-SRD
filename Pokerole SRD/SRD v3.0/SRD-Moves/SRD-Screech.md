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
  SoundMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: A mighty screech will make the target cover its ears instead of covering
  its flanks.
Effect: Single Target. Sound Move. Reduce the Target's Defense by 2.
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