---
Accuracy1: Beauty
Accuracy2: Perform
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -2
    Stats:
    - Strength
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: A beautiful dance that soothes the hearts of those who watch it, reducing
  their aggressive intentions.
Effect: Reduce the foe's Strength by 2.
Name: Feather Dance
Power: 0
Target: Foe
Type: Flying
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