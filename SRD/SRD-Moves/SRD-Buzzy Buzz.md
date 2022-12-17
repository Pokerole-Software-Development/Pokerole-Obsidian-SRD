---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  Ailments:
  - Affects: Targets
    Type: Paralyze
Attributes: {}
Damage1: Special
Damage2: ''
Description: The Pokemon releases a jolt of static electricity from its fur, that
  makes a cute zapping sound. It's all fun and games until somebody gets paralyzed.
DmgType: Special
Effect: Paralyze the foe. If the user of this Move is at its Final Stage of Evolution,
  this move fails.
Name: Buzzy Buzz
Power: 3
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