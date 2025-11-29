---
Accuracy1: Clever
Accuracy2: Perform
AddedEffects: {}
Attributes:
  CopyMove: true
  Duration: Permanent
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon draws a rough sketch of their target performing a Move\
  \ and through their art studies they manage to learn that same Move in the process."
Effect: Single Target. Copy Move. Replace "Sketch" with the copied Move. Permanent
  Duration.
Name: Sketch
Power: 0
Target: Foe
Type: Normal
---

#PokeroleSRD/Moves

### `= this.name`
*`= this.Description`*

**Accuracy:** `= this.Accuracy1` + `= this.Accuracy2`
**Damage:** `= this.Power` `= choice(length(this.Damage1)=0, "","\+ "+ this.Damage1)` `= choice(length(this.Damage2)=0, "","\+ "+ this.Damage2)`

| Type          | Target          | Category          | Power          |
| ------------- | --------------- | ----------------  | -------------- |
| `= this.Type` | `= this.Target` | `= this.Category` | `= this.Power` | 

**Effect:** `= this.Effect`