---
Accuracy1: Special
Accuracy2: Nature
AddedEffects:
  Heal:
    Type: Basic
Attributes: {}
Damage1: ''
Damage2: ''
Description: The Pokemon concentrates on restoring its own cells faster than anything
  imaginable.
DmgType: Support
Effect: Basic Heal. If successful, spend 1 Will point to activate. May cure Lethal
  Damage.
Name: Recover
Power: 0
Target: User
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