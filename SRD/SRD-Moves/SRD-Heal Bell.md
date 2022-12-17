---
Accuracy1: Special
Accuracy2: Perform
AddedEffects:
  AilmentHeal:
  - All
Attributes:
  SoundBased: true
Damage1: ''
Damage2: ''
Description: The Pokemon chimes a magical bell. Legend says the soothing sound has
  healing properties.
DmgType: Support
Effect: Cure the User and allies suffering from Status Conditions. They don't need
  to be on the battlefield to get this effect. Sound Based.
Name: Heal Bell
Power: 0
Target: User and Allies
Type: Normal
---

#PokeroleSRD/Moves

### `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`