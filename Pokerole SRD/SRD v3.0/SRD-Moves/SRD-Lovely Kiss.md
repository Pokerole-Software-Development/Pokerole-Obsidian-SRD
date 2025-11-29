---
Accuracy1: MissingBeautyPoints
Accuracy2: ''
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Sleep
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "A true love\u2019s kiss that could turn any prince into a froakie and\
  \ put any princess to sleep for a hundred years."
Effect: Single Target. Put the Target to Sleep. Pokemon with this Move may forfeit
  their Beauty score completely, restore 1 Point to their Beauty Score. If the Pokemon
  forgets this move, restore 1 point to their Beauty Score.
Name: Lovely Kiss
Power: 0
Target: Foe
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