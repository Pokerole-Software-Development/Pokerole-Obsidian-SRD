---
Accuracy1: Vitality
Accuracy2: Nature
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: 3
    Stats:
    - Def
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon grows a lush coat of cotton puffs. The cotton greatly\
  \ reduces all kinds of impact."
Effect: Target Self. Increase the User's Defense by 3.
Name: Cotton Guard
Power: 0
Target: Self
Type: Grass
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