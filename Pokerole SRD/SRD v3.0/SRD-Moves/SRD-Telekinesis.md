---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Telekinesis
  - Affects: Targets
    Type: Hovering
Attributes:
  Duration: 2
Category: Support
Damage1: ''
Damage2: ''
Description: "The target levitates from the ground as the user\u2019s telekinetic\
  \ powers prevent its movement."
Effect: Single Target. Target becomes immune to Ground-Type Moves. Target can't Evade.
  Duration 2 Rounds.
Name: Telekinesis
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