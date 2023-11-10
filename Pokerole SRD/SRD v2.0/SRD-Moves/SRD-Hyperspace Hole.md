---
Accuracy1: Insight
Accuracy2: Channel
AddedEffects: {}
Attributes:
  IgnoreShield: true
Category: Special
Damage1: Special
Damage2: ''
Description: The user knows the laws of physics bind it from being in many places
  at once and forbid it from occupying the same space as other bodies. It just disregards
  their authority.
Effect: Ignore Defenses. Never Miss. This Move Bypasses the effects of any Shield
  Move effect on the foe.
Name: Hyperspace Hole
Power: 3
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