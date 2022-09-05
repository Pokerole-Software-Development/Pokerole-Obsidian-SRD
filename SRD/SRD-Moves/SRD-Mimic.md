---
Accuracy1: Clever
Accuracy2: Perform
Damage1: ''
Damage2: ''
Description: Making use of its acting talents, the Pokemon imitates what the target
  just did.
DmgType: Support
Effect: Copies the last move the target used until the end of the scene. That move
  replaces Mimic.
Name: Mimic
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