---
Accuracy1: Special
Accuracy2: Channel
Damage1: ''
Damage2: ''
Description: The user spits some of its own gastric juices, the acid prevents the
  foe from using its special abilities.
DmgType: Support
Effect: Until the end of the Scene, eliminate any effect the foe's Ability would do.
Name: Gastro Acid
Power: 0
Target: Foe
Type: Poison
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