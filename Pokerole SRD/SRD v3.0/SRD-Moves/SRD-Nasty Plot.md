---
Accuracy1: Clever
Accuracy2: Alert
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: 2
    Stats:
    - Special
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "Rubbing both hands and laughing sinisterly the Pok\xE9mon rejoices in\
  \ the evil plans they\u2019ll soon carry out."
Effect: Target Self. Increase User's Special by 2.
Name: Nasty Plot
Power: 0
Target: Self
Type: Dark
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