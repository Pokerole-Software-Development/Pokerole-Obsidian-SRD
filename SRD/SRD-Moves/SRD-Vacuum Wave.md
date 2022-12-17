---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects: {}
Attributes:
  Priority: 1
Damage1: Special
Damage2: ''
Description: The user pulls the enemy closer using the power of its ki. This traction
  has a lot of strength and may break anything it pulls.
DmgType: Special
Effect: Priority 1.
Name: Vacuum Wave
Power: 2
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