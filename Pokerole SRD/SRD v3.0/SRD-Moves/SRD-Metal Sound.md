---
Accuracy1: Tough
Accuracy2: Perform
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -2
    Stats:
    - SpDef
Attributes:
  SoundMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: "A horrible screeching sound rumbles in the foe\u2019s ears. Some people\
  \ will try to convince you that this is good music."
Effect: Single Target. Sound Move. Reduce the Target's Sp. Defense by 2.
Name: Metal Sound
Power: 0
Target: Foe
Type: Steel
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