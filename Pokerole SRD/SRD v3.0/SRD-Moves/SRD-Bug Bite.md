---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  BiteMove: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The Pok\xE9mon nibbles at their foe in hopes of finding something tasty\
  \ to snack on."
Effect: Single Target. Bite Move. If the target Pokemon is holding a berry, the User
  eats it and gains its effects.
Name: Bug Bite
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