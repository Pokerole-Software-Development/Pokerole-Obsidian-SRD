---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  SwitcherMove: User
Category: Special
Damage1: Special
Damage2: ''
Description: The user shoots a wave of electric rings that allow it to reteat to safety
  at the speed of lightning.
Effect: Single Target. Switcher Move for the User.
Name: Volt Switch
Power: 2
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