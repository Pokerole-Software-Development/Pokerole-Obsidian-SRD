---
Accuracy1: Strength
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  HurtPenalty: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: "The foe is grappled in a painful lock, the more it struggles to get\
  \ out the more pressure it\u2019s gonna feel. The user must be on top condition\
  \ for this grapple to be effective."
Effect: Single Target. *Reduce 1 Die from the Damage Pool for every missing Hp the
  User has. Up to 5 Dice may be removed this way.
Name: Hard Press
Power: 6
Target: Foe
Type: Steel
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