---
Accuracy1: Insight/Strength
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Grounded
  TerrainEffect: Gravity
Attributes:
  Duration: 4
Category: Support
Damage1: ''
Damage2: ''
Description: An invisisible force pulls everyone to the floor keeps them from taking
  off the ground.
Effect: Target Battlefield. Remove the immunity to Ground-Type Moves for everyone
  in the field. Moves that require jumping or flying get an Extra "Low Accuracy 2".
  Duration 4 Rounds.
Name: Gravity
Power: 0
Target: Battlefield
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