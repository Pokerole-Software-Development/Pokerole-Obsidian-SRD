---
Accuracy1: Insight
Accuracy2: Perform
AddedEffects: {}
Attributes:
  NeverFail: true
  SoundBased: true
Category: Special
Damage1: Special
Damage2: ''
Description: With a charming and manipulative cry, the user deals emotional damage
  to its opponent. This move always makes the target feel bad.
Effect: Sound Based. Never Fail. Targets All foes in range.
Name: Disarming Voice
Power: 2
Target: All Foes
Type: Fairy
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