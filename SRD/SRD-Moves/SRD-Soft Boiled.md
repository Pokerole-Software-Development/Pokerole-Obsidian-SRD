---
Accuracy1: Insight
Accuracy2: Nature
AddedEffects:
  Heal:
    Type: Basic
Attributes: {}
Damage1: ''
Damage2: ''
Description: The user boils a freshly layed egg and restores Health with the energy
  stored within.
DmgType: Support
Effect: Basic Heal. If successful spend 1 Will point to activate.
Name: Soft Boiled
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