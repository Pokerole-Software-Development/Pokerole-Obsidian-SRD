---
Accuracy1: Same as the copied move
Accuracy2: ''
AddedEffects: {}
Attributes: {}
Damage1: Same as the copied move
Damage2: ''
Description: The user will closely watch the movements of the target and will imitate
  them to perfection.
DmgType: Support
Effect: Copies the last move the foe has performed.
Name: Copycat
Power: 0
Target: Foe
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