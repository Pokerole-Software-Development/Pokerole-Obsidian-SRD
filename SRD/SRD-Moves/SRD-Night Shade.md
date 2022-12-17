---
Accuracy1: Insight
Accuracy2: Channel
AddedEffects: {}
Attributes:
  IgnoreDefenses: true
Damage1: ''
Damage2: ''
Description: The user casts a shade with a frightening mirage inside that torments
  the target.
DmgType: Special
Effect: Roll Damage Dice according to the User's Rank. 1 Dice at Starter Rank. 2 Dice
  at Beginner Rank.  3 dice at Amateur Rank.  4 Dice at Ace Rank.  5 Dice at Professional
  Rank. Ignores Defense.
Name: Night Shade
Power: 0
Target: Foe
Type: Ghost
---

#PokeroleSRD/Moves

### `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`