---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The user employs its psychic power to average its resilience with the
  foe. They both feel like they're equals in terms of toughness.
Effect: Average your Defense and Sp. Defense with your target.
Name: Guard Split
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