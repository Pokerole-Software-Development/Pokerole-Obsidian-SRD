---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  NeverFail: true
Damage1: Special
Damage2: ''
Description: The user quickly releases jolts of electricity that are too fast for
  many to react.
DmgType: Special
Effect: Never Fail.
Name: Shock Wave
Power: 2
Target: Foe
Type: Electric
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