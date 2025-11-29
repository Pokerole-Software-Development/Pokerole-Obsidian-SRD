---
Accuracy1: Insight
Accuracy2: Alert
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: LaserFocus
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "Through its incredible awarenes the Pok\xE9mon finds a straight path\
  \ into a weak point of the foe. The attack that follows is devastating."
Effect: Target Self. If the next Physical or Special Move the user performs gets 5
  more successes required on the Accuracy Roll, ignore the Target's defenses on the
  Damage roll.
Name: Laser Focus
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