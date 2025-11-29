---
Accuracy1: Cool
Accuracy2: Perform
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: FollowMeSpotlight
Attributes:
  Duration: 1
  Reaction: '5'
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pokemon draws everyone\u2019s attention, provoking their foes to\
  \ do their worse."
Effect: Target Self. Reaction 5. All Foe's Moves able to do so will Target the user.
  Duration 1 Round.
Name: Follow Me
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