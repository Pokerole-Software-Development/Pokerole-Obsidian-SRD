---
Accuracy1: Tough
Accuracy2: Intimidate
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -1
    Stats:
    - Strength
    - Special
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The Pokemon makes a roar that commands respect and authority over anyone
  listening.
Effect: Reduce the foe's Strength and Special.
Name: Noble Roar
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