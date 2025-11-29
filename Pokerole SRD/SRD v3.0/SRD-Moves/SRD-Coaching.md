---
Accuracy1: Cool/Clever
Accuracy2: Athletic
AddedEffects: {}
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "This Pok\xE9mon allies form a line and start doing squats and push-ups\
  \ while the user corrects their form and gives them tips and a confidence boost\
  \ to win this match."
Effect: Target All Allies in Range. Increase by 1 the Strength and Defense of all
  Allies targeted. The User cannot target itself.
Name: Coaching
Power: 0
Target: User and Allies
Type: Fighting
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