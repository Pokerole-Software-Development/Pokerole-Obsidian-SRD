---
Accuracy1: Cool
Accuracy2: Perform
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: FollowMeSpotlight
Attributes:
  Priority: 5
Category: Support
Damage1: ''
Damage2: ''
Description: The Pokemon will draw everyone's attention. All foes are taunted to do
  their worst.
Effect: Foes will target the user this Round. Priority 5.
Name: Follow Me
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