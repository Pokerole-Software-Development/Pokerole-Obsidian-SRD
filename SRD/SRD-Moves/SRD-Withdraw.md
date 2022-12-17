---
Accuracy1: Vitality
Accuracy2: Brawl
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: 1
    Stats:
    - Def
Attributes: {}
Damage1: ''
Damage2: ''
Description: The user hides inside its hard shell to protect itself from incoming
  attacks.
DmgType: Support
Effect: Increase User's Defense.
Name: Withdraw
Power: 0
Target: User
Type: Water
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