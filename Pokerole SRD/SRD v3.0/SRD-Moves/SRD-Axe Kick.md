---
Accuracy1: Dexterity
Accuracy2: Brawl
AddedEffects: {}
Attributes:
  IgnoreDefenses: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: The user attacks by kicking up into the air and slamming its heel down
  upon the target leaving it both allured and scared. The heel may break if the kick
  fails.
Effect: Single Target. Roll 3 Chance Dice to Confuse the Target. If the Accuracy roll
  fails, Roll 4 Dice of Typeless Damage against the user, ignoring defenses.
Name: Axe Kick
Power: 5
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