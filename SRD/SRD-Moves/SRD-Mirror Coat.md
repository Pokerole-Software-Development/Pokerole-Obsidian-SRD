---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  IgnoreDefenses: true
Category: Special
Damage1: ''
Damage2: ''
Description: The user canalizes the damage received by energies and bounces them back
  to their source.
Effect: The move only works if the foe just used a Special Attack. Roll the same Damage
  Pool as your foe's last attack and add 2 Extra Damage Dice. Ignore the foe's Defenses.
Name: Mirror Coat
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