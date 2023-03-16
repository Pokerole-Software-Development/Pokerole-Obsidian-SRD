---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -1
    Stats:
    - Dexterity
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: Shoots an electrified web at all foes to restrict their movement. Walking
  through this web can be painful.
Effect: Reduce Dexterity of those affected.
Name: Electroweb
Power: 2
Target: All Foes
Type: Electric
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