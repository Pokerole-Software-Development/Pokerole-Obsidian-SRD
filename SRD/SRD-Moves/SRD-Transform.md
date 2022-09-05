---
Accuracy1: Will
Accuracy2: Channel
Damage1: ''
Damage2: ''
Description: The user modifies its own DNA structure to become an identical clone
  of any Pokemon or object it can see.
DmgType: Support
Effect: The user transforms into a copy of its target with same Ability, Attributes,
  Trait Modifiers, and Moves. Being inside a Pokeball breaks the Transformation.
Name: Transform
Power: 0
Target: User
Type: Normal
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