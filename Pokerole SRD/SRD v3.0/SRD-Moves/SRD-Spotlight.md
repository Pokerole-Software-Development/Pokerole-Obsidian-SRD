---
Accuracy1: Cool
Accuracy2: Perform
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: FollowMeSpotlight
Attributes:
  Duration: 1
  Reaction: '3'
Category: Support
Damage1: ''
Damage2: ''
Description: "The user points a focused light onto one of their allies. The ally can\u2019\
  t help but catch everyone\u2019s attention into itself."
Effect: Target One Ally. Reaction 3. All of the Foe's Moves will Target the Chosen
  Ally if able. Duration 1 Round.
Name: Spotlight
Power: 0
Target: Ally
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