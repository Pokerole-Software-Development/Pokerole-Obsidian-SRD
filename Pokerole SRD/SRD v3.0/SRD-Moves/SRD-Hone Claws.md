---
Accuracy1: Insight
Accuracy2: Intimidate
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: 1
    Stats:
    - Strength
    - Accuracy
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: Sharp claws make for more precise and deadly attacks.
Effect: Target Self. Increase by 1 the User's Strength score and Accuracy Pools.
Name: Hone Claws
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