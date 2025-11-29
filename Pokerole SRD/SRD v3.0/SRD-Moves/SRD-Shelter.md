---
Accuracy1: Vitality
Accuracy2: Nature/Stealth
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: 1
    Stats:
    - SpDef
    - Def
  - Affects: Targets
    Stages: -1
    Stats:
    - Accuracy
Category: Support
Damage1: ''
Damage2: ''
Description: "The user uses a sturdy part of their body as a shelter to hide. It\u2019\
  s difficult for the foes to find an opening."
Effect: Target Self. Increase by 1 the User's Defense and Sp. Defense. Reduce 1 success
  to all the Accuracy Rolls of the Foes when targeting the User.
Name: Shelter
Power: 0
Target: Self
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