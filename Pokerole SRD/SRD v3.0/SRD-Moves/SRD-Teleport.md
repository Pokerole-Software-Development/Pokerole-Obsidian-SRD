---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  SwitcherMove: User
Category: Support
Damage1: ''
Damage2: ''
Description: "Now you see me. Now you don\u2019t."
Effect: Target Self. Switcher Move for the User. Out of battle, Teleportation distances
  and limitations are determined by the User's Special Score and Storyteller's discretion.
Name: Teleport
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