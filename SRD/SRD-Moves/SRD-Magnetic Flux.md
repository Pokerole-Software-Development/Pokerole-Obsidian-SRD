---
Accuracy1: Insight
Accuracy2: Nature
Damage1: ''
Damage2: ''
Description: The Pokemon bends the magnetic field around itself, this also affects
  all allies who are sensible to it.
DmgType: Support
Effect: Increase the Defense and Sp. Defense of User and all its Electric and Steel
  Type Allies.
Name: Magnetic Flux
Power: 0
Target: User and Allies
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