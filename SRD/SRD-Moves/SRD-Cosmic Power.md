---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: 1
    Stats:
    - Def
    - SpDef
Attributes: {}
Damage1: ''
Damage2: ''
Description: The user absorbs power from space. This Pokemon glows faintly with energy
  afterwards.
DmgType: Support
Effect: Increase the User's Defense and Sp. Defense.
Name: Cosmic Power
Power: 0
Target: User
Type: Psychic
---

#PokeroleSRD/Moves

### `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`