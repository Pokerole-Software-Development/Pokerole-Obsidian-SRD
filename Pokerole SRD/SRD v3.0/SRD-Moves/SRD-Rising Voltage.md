---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Lethal: true
Category: Special
Damage1: Special
Damage2: ''
Description: A shockwave travels through the ground, then rises as a golden pillar
  of thunderbolts.
Effect: Single Target. Lethal. *If Electric Terrain is active, add 3 Extra Dice to
  the Damage pool of this Move.
Name: Rising Voltage
Power: 3
Target: Foe
Type: Electric
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