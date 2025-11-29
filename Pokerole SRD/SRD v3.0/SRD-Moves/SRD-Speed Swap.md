---
Accuracy1: Insight
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: User
    Type: SpeedSwap
  - Affects: Targets
    Type: SpeedSwap
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: This move allows the user to release its power. If the user has any boosts,
  the damage is increased.
Effect: Single Target. Switch the User's Dexterity with the Target's.
Name: Speed Swap
Power: 0
Target: Foe
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