---
Accuracy1: Vitality
Accuracy2: Athletic
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: 1
    Stats:
    - Strength
    - Def
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The Pokemon shows its muscles with intimidating poses to look bigger
  and stronger.
Effect: Increase the User's Strength and Defense.
Name: Bulk Up
Power: 0
Target: User
Type: Fighting
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