---
Accuracy1: Will
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -2
    Stats:
    - Strength
    - Dexterity
    - Special
    - Def
    - SpDef
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: The user unleashes all its remaining power to send a wave of hopeless
  thoughts to haunt the foe's mind and soul. The target will be left in grief.
Effect: The user faints. Reduce foe's Strength. Dexterity. Special. Defense and Sp.
  Defense by 2. Lasts for a whole scene.
Name: Memento
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