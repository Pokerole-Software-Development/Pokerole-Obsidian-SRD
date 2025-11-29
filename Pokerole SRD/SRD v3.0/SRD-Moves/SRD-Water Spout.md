---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  HurtPenalty: true
  Lethal: true
Category: Special
Damage1: Special
Damage2: ''
Description: This Move alone may be the reason the earth is 70% water.
Effect: Target All Foes in Range. Lethal. *Reduce 1 Die from the Damage Pool for every
  missing HP the User has. Up to 5 Dice may be removed this way.
Name: Water Spout
Power: 6
Target: All Foes
Type: Water
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