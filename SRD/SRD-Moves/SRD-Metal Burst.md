---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects: {}
Attributes: {}
Category: Physical
Damage1: ''
Damage2: ''
Description: After receiving damage, the user bursts the tiny but sharp metal piece
  that came loose because of the foe's attack. The greater the impact the more metal
  it will shoot.
Effect: This Move only works if the foe just used an attack. Roll the same Damage
  Pool as your foe's last attack and add 2 Extra Damage Dice.
Name: Metal Burst
Power: 0
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