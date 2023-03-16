---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  SwitcherMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: The user stores part of its power on a twig or a stick, anyone who touch
  the item will receive its might.
Effect: "Switcher Move. User switches out with another Pokemon. Any Attribute increase\
  \ on the user is passed on the next Pokemon. The user can\u2019t increase its Attributes\
  \ again until the end of the scene."
Name: Baton Pass
Power: 0
Target: User
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