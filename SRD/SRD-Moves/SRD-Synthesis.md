---
Accuracy1: Special
Accuracy2: Nature
Damage1: ''
Damage2: ''
Description: The Pokemon uses the sunlight as energy to regain its vitality.
DmgType: Support
Effect: Basic Heal. If Successful spend 1 Will point to activate. If performed under
  Sunny weather this Move is a Complete Heal. If Rain/Sandstorm Weather is in effect
  this move only heals 1 HP.
Name: Synthesis
Power: 0
Target: User
Type: Grass
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