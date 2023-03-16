---
Accuracy1: Cute
Accuracy2: Perform
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -2
    Stats:
    - SpDef
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The user stops battling and feigns to be crying, disrupting the foe's
  mood to battle and making it lower its guard.
Effect: Reduce the foe's Sp. Defense by 2.
Name: Fake Tears
Power: 0
Target: Foe
Type: Dark
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