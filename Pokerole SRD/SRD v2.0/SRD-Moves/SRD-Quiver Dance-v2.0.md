---
Accuracy1: Beauty
Accuracy2: Perform
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: 1
    Stats:
    - Dexterity
    - Special
    - SpDef
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: A mystical and beautiful dance that boosts a Pokemon's dexterity and
  focus.
Effect: Increases Dexterity, Special, and Sp. Defense.
Name: Quiver Dance
Power: 0
Target: User
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