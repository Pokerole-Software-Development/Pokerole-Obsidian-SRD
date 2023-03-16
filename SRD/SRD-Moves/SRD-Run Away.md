---
Accuracy1: Dexterity
Accuracy2: Athletic
AddedEffects: {}
Attributes: {}
Damage1: ''
Damage2: ''
Description: ''
DmgType: Support
Effect: 'The User runs away from the battlefield. This effect ends the battle. Foes
  might try to prevent this by rolling: Dexterity + Athletic and scoring the same
  or more successes. If the user is Blocked this Maneuver fails.'
Name: Run Away
Power: 0
Target: User
Type: Typeless
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