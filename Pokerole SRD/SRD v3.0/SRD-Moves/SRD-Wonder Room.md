---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: WonderRoom
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The battlefield is now a space that puts the mind to the test. A resilient
  mind will be a resilient body, but if the mind is weak the body will feel frail
  and feeble.
Effect: Target the Battlefield. Everyone on the Battlefield will have their Defense
  and Sp. Defense calculated with Insight instead of Vitality. If using Insight as
  Sp. Defense optional rule, swap the calculation. Duration 4 Rounds.
Name: Wonder Room
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