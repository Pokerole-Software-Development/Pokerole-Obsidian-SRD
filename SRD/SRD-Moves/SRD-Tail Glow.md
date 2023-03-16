---
Accuracy1: Insight
Accuracy2: Nature
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: 3
    Stats:
    - Special
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The user emits a strong light. This Pokemon will stare at its brightness
  to enter a trance.
Effect: Increase the User's Special by 3.
Name: Tail Glow
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