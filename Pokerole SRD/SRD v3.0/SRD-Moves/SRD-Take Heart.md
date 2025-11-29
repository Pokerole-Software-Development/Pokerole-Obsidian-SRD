---
Accuracy1: Will
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: 1
    Stats:
    - Special
    - SpDef
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "There\u2019s something only you can do so that this blue planet doesn\u2019\
  t lose it\u2019s light. Believe in yourself and show your brave heart."
Effect: Target Self. Heal any Status Ailment on the User. Increase by 1 the User's
  Special and Sp. Defense.
Name: Take Heart
Power: 0
Target: Self
Type: Psychic
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