---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  NeverFail: true
Damage1: Special
Damage2: ''
Description: The user channels its aura and launches this power in the form of a sphere
  The foe's aura is hit, leaving the target unscratched but deeply hurt.
DmgType: Special
Effect: Never Fail.
Name: Aura Sphere
Power: 3
Target: Foe
Type: Fighting
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