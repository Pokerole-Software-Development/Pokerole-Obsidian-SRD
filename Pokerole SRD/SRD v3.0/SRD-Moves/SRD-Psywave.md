---
Accuracy1: Insight
Accuracy2: Intimidate
AddedEffects: {}
Attributes:
  IgnoreDefenses: true
Category: Special
Damage1: Varies
Damage2: ''
Description: "A powerful mental wave assault\u2019s the target\u2019s brain directly.\
  \ Everything, from forgotten memories to the secrets of the universe bombard its\
  \ mind in just a few seconds."
Effect: 'Single Target. Roll Psychic-Type Damage Dice according to the User''s Rank:
  Starter 1 Die / Rookie 2 Dice / Standard 4 Dice/ Advacned 6 Dice / Expert 8 Dice
  / Ace and forward 10 Dice. Ignore Defenses.'
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