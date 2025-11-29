---
Accuracy1: Clever
Accuracy2: Stealth
AddedEffects: {}
Attributes:
  IgnoreShield: true
  LateReaction: '1'
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user begins their attack, and as their target attempts to protect
  itself, the user feints the target to break their defense against their true strike.
Effect: Single Target. Late Reaction 1. This Move ignores the effects of any Shield
  Move active on the Target and removes their effects for the rest of the Round.
Name: Feint
Power: 1
Target: Foe
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