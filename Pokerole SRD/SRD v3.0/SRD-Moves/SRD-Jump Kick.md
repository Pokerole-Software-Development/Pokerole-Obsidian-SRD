---
Accuracy1: Dexterity
Accuracy2: Athletic
AddedEffects: {}
Attributes:
  AccuracyReduction: -1
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user launches itself up two stories high to pummel down with a powerful
  kick. Do not try it at home.
Effect: Single Target. Low Accuracy 1. If the Accuracy roll fails, Roll 4 Dice of
  Typeless Damage against the user, ignoring defenses.
Name: Jump Kick
Power: 4
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