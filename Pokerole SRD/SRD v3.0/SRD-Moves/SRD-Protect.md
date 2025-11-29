---
Accuracy1: Will
Accuracy2: Alert
AddedEffects: {}
Attributes:
  Reaction: '5'
  ShieldMove: true
Category: Support
Damage1: ''
Damage2: ''
Description: A mighty energy shield materializes in front of the user to to deflect
  attacks and dispel ill effects.
Effect: Target Self. Reaction 5. Shield Move. Reduce 3 Damage this Pokemon would receive
  from a Physical or Special Move. Negate the Added Effects of Moves that target the
  user.
Name: Protect
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