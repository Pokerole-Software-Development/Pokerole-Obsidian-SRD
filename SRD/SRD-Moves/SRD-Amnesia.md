---
Accuracy1: Insight
Accuracy2: Alert
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: 2
    Stats:
    - SpDef
Attributes: {}
Damage1: ''
Damage2: ''
Description: As a fine example of mind over matter, the user temporarily empties its
  mind to make it more resilient.
DmgType: Support
Effect: Increase the User's Sp. Defense by 2.
Name: Amnesia
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