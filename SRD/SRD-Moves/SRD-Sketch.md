---
Accuracy1: DEXTERITY
Accuracy2: PERFORM
Damage1: ''
Damage2: ''
Description: The Pokemon draws its foe performing a move. It learns how to perform
  that move in the process.
DmgType: SUPPORT
Effect: Permanently copies a move the target used. Once Copied "Sketch" disappears.
Name: Sketch
Power: 0
Target: Foe
Type: Normal
---

#PokeroleSRD/Moves

## `= this.name` 
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Damage Type          | Power          |
| ------------- | --------------- | ---------------- | -------------- |
| `= this.Type` | `= this.Target` | `= this.DmgType` | `= this.Power` | 

**Effect:** `= this.Effect`