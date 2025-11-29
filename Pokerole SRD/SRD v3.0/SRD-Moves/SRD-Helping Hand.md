---
Accuracy1: Cool
Accuracy2: Alert
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: HelpingHand
Attributes:
  Reaction: '5'
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon is the first to come and give a hand to their friend.\
  \ A true bro."
Effect: Target One Ally. Reaction 5. The Target Gets 2 Extra Dice on their next Skill
  Check/Accuracy Roll, and 2 Extra Dice on their next Damage Roll. This Effect does
  not Stack.
Name: Helping Hand
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