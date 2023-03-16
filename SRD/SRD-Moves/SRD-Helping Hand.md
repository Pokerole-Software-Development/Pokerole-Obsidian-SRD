---
Accuracy1: Dexterity
Accuracy2: Perform
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: HelpingHand
Attributes:
  Priority: 5
Category: Support
Damage1: ''
Damage2: ''
Description: The Pokemon assists an ally. Together they are stronger.
Effect: Target Pokemon gets 2 Extra Dice on its next Skill, Accuracy and Damage Rolls.
  Priority 5.
Name: Helping Hand
Power: 0
Target: One Ally
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