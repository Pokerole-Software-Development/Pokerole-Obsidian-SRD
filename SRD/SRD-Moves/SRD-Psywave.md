---
Accuracy1: Insight
Accuracy2: Channel
AddedEffects: {}
Attributes:
  IgnoreDefenses: true
Category: Special
Damage1: ''
Damage2: ''
Description: Releases the inner power of the mind to emanate psychic waves that hurt
  the target.
Effect: Roll Damage Dice according to the User's Rank. 1 Dice at Starter Rank. 2 Dice
  at Beginner Rank. 3 dice at Amateur Rank. 4 Dice at Ace Rank. 5 Dice at Professional
  Rank. Ignores Defense.
Name: Psywave
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