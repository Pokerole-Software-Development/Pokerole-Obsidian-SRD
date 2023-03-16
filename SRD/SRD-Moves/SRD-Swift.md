---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  NeverFail: true
Category: Special
Damage1: Special
Damage2: ''
Description: The user shoots a star shaped light beam that hits the target at blinding
  speed.
Effect: Never Fail.
Name: Swift
Power: 2
Target: All Foes
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