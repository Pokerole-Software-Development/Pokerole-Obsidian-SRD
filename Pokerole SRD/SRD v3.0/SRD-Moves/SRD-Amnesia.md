---
Accuracy1: Clever
Accuracy2: Alert
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: 2
    Stats:
    - SpDef
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: No thoughts. Head empty
Effect: Target Self. Increase the User's Sp. Defense by 2.
Name: Amnesia
Power: 0
Target: Self
Type: Psychic
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