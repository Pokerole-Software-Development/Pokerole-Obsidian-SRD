---
Accuracy1: Special
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -1
    Stats:
    - Accuracy
Attributes: {}
Damage1: ''
Damage2: ''
Description: The user convers its foe with a cloud of smoke. Some Pokemon hide inside
  this screen while others use it as a cover to escape.
DmgType: Support
Effect: Reduce the foe's Accuracy.
Name: Smokescreen
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