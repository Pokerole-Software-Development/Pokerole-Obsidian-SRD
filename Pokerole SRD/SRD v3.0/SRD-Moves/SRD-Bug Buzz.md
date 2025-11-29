---
Accuracy1: Special
Accuracy2: Perform
AddedEffects:
  StatChanges:
  - Affects: Targets
    ChanceDice: 1
    Stages: -1
    Stats:
    - SpDef
Attributes:
  SoundMove: true
Category: Special
Damage1: Special
Damage2: ''
Description: "The Pok\xE9mon uses their wings or a part of their bodies to emit distracting\
  \ buzzes all around."
Effect: Target All Foes in Range. Sound Move. Roll 1 Chance Die to Reduce by 1 the
  Sp. Defense of those affected.
Name: Bug Buzz
Power: 3
Target: All Foes
Type: Bug
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