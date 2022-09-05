---
Accuracy1: Special
Accuracy2: Nature
Damage1: ''
Damage2: ''
Description: The Pokemon releases an aroma that its enemies will love.
DmgType: Support
Effect: Those affected cannot evade moves performed by the user. Attracts wild Pokemon
  if used outside of battle.
Name: Sweet Scent
Power: 0
Target: All Foes
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