---
Accuracy1: Dexterity
Accuracy2: Athletic
AddedEffects: {}
Attributes:
  SwitcherMove: User
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon rallies through the battle, setting up everything for\
  \ the next companion as they know this is a team effort."
Effect: Target Self. Switcher Move for the User. Any Attribute increase on the user
  is passed on the next Pokemon. The user can't increase its own Attributes again
  until the end of the scene or until the switched Pokemon faints.
Name: Baton Pass
Power: 0
Target: Self
Type: Normal
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