---
Accuracy1: Dexterity
Accuracy2: Athletic
AddedEffects: {}
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: Nope. Nope. Nope.
Effect: Target Self. The User runs away from the Battlefield. This Effect ends the
  Battle. Foes may try to prevent this by rolling Dexterity + Athletic and scoring
  the same or more Successes. If the User is Blocked, this Maneuver fails.
Name: Run Away
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