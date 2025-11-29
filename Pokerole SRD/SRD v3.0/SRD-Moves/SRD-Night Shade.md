---
Accuracy1: Insight/Special
Accuracy2: Intimidate
AddedEffects: {}
Attributes:
  IgnoreDefenses: true
Category: Special
Damage1: Varies
Damage2: ''
Description: The user casts a dark and frightening mirage surrounding the foe to give
  them a panic attack.
Effect: 'Single Target. Roll Ghost-Type Damage Dice according to the User''s Rank:
  Starter 1 Die / Rookie 2 Dice / Standard 4 Dice/ Advacned 6 Dice / Expert 8 Dice
  / Ace and forward 10 Dice. Ignore Defenses.'
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

| Type          | Target          | Category          | Power          |
| ------------- | --------------- | ----------------  | -------------- |
| `= this.Type` | `= this.Target` | `= this.Category` | `= this.Power` | 

**Effect:** `= this.Effect`