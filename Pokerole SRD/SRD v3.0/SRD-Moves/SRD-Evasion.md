---
Accuracy1: Dexterity
Accuracy2: Evasion
AddedEffects: {}
Attributes:
  Reaction: 6
Category: Support
Damage1: ''
Damage2: ''
Description: No time to think! If you hear "Dooooooodge!" You get out of the way A.S.A.P
Effect: Target Self. Reaction 6. Match the number of successes on the Accuracy roll
  ofa Move that targets the User. If successful, the user Evades, see p.68. This Maneuver
  is not affected by the Multiple Action difficulty chart.
Name: Evasion
Power: 0
Target: User
Type: Typeless
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