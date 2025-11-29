---
Accuracy1: MissingCoolPoints
Accuracy2: ''
AddedEffects: {}
Attributes:
  Duration: 4
  SwitcherMove: User
Category: Support
Damage1: ''
Damage2: ''
Description: "\u201CWhat did a Geodude say to another Geodude? Let\u2019s Rock!\u201D\
  \ The User tells a joke so terrible the whole battlefield freezes. Afterwards, the\
  \ user retreats in shame."
Effect: Target Battlefield. Switcher Move For the User. Activate Snowy Weather. Duration
  4 Rounds. Pokemon with this Move may forfeit their Cool score completely. If the
  Pokemon forgets this Move, restore 1 Point to their Cool Score.
Name: Chilly Reception
Power: 0
Target: Battlefield
Type: Ice
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