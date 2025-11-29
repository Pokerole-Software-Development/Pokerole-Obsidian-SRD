---
Accuracy1: Dexterity
Accuracy2: Stealth
AddedEffects: {}
Attributes: {}
Category: Physical
Damage1: Target'sStrength/Special
Damage2: ''
Description: The user feints an attack that tricks the foe into hurting itself.
Effect: Single Target. S.T.A.B. of the User and the Strength/Special of the foe are
  used for this Move's Damage Pool.
Name: Foul Play
Power: 3
Target: Foe
Type: Dark
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