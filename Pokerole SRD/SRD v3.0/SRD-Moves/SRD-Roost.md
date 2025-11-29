---
Accuracy1: Clever
Accuracy2: Nature
AddedEffects:
  Ailments:
  - Affects: User
    Type: Grounded
  Heal:
    Target: Targets
    Type: Basic
    WillPointCost: 1
Attributes:
  Duration: 1
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon gathers some twigs and builds themselves a comfy nest\
  \ on the floor to roost and relax."
Effect: Target Self. Basic Heal. If successful, spend 1 Will point to activate. Remove
  the User's Immunity to Ground-Type Moves. Duration 1 Round.
Name: Roost
Power: 0
Target: Self
Type: Flying
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