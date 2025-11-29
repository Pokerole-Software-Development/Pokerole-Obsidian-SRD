---
Accuracy1: Special
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Lethal: true
  Ranged: true
Category: Physical
Damage1: Strength
Damage2: ''
Description: With the flick of a wand the user is spun around in a magic swirl that
  leaves them absolutely dizzy.
Effect: Single Target. Lethal. Ranged. Roll 3 Chance dice to Confuse the Target.
Name: Magical Torque
Power: 4
Target: Foe
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