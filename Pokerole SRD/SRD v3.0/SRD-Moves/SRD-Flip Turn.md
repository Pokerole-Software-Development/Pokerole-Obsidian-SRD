---
Accuracy1: Dexterity
Accuracy2: Athletic
AddedEffects: {}
Attributes:
  SwitcherMove: User
Category: Physical
Damage1: Strength
Damage2: ''
Description: Charge at the foe as a cannon ball made out of water. The big splash
  causes bystanders to lose sight on the battlefield. When the splash settles, the
  user is gone.
Effect: Single Target. Switcher Move for the User.
Name: Flip Turn
Power: 2
Target: Foe
Type: Water
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