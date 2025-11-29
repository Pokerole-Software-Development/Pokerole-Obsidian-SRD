---
Accuracy1: Special
Accuracy2: Nature
AddedEffects: {}
Attributes:
  AccuracyReduction: -2
  Lethal: true
Category: Special
Damage1: Special
Damage2: ''
Description: The whole battlefield becomes engulfed in a maelstrom of emotion. Love
  and hate deal emotional damage to those unfortunate enough to be trapped into it.
Effect: 'Area Move. Lethal. Low Accuracy 2. *Choose one: Roll 3 Chance Dice to increase
  by 1 the User''s Strength, Special, Dexterity, Defense & Sp. Defense. Or, Roll 3
  Chance dice to Reduce by 2 the affected Defense & Sp. Defense.'
Name: Springtide Storm
Power: 4
Target: Area
Type: Fairy
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