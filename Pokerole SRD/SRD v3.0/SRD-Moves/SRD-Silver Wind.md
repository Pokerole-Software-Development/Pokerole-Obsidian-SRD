---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: User
    ChanceDice: 1
    Stages: 1
    Stats:
    - Strength
    - Dexterity
    - Special
    - Def
    - SpDef
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: A beautiful but dangerous wind that blows a silver powder against the
  foe. The performance may give the user a big confidence boost.
Effect: Single Target. Roll 1 Chance Die to Increase by 1 the User's Strength, Dexterity,
  Special, Defense, and Sp. Defense.
Name: Silver Wind
Power: 2
Target: Foe
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