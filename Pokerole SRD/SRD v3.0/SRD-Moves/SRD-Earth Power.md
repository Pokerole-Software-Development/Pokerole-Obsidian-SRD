---
Accuracy1: Special
Accuracy2: Nature
AddedEffects:
  StatChanges:
  - Affects: Targets
    ChanceDice: 1
    Stages: -1
    Stats:
    - SpDef
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: "The user sends out a subterranean wave that bursts the ground below\
  \ the target. It\u2019s as if the earth bends to the user\u2019s will."
Effect: Single Target. Roll 1 Chance Die to Reduce the Target's Sp. Defense by 1.
Name: Earth Power
Power: 3
Target: Foe
Type: Ground
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