---
Accuracy1: Strength
Accuracy2: Athletic
AddedEffects: {}
Attributes:
  IgnoreDefenses: true
Category: Physical
Damage1: Varies
Damage2: ''
Description: The foe gets launched up to the sky, then falls face-first into the ground
  making it tremble. The stronger the user, the higher the launch.
Effect: 'Single Target. Roll Fight-Type Damage Dice according to the User''s Rank:
  Starter 1 Die / Rookie 2 Dice / Standard 4 Dice/ Advacned 6 Dice / Expert 8 Dice
  / Ace and forward 10 Dice. Ignore Defenses.'
Name: Seismic Toss
Power: 0
Target: Foe
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