---
Accuracy1: Insight
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  IgnoreDefenses: true
Category: Physical
Damage1: ''
Damage2: ''
Description: The user prepares to receive damage, then returns the same damage and
  more.
Effect: This Move can only deal damage if the Foe has dealt Physical Damage to the
  User this Round. Roll the same Damage Pool as your Foe plus 2 Extra Dice. Ignore
  the foe's Defenses.
Name: Counter
Power: 2
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