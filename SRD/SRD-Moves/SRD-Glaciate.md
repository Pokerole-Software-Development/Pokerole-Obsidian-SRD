---
Accuracy1: Dexterity
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -1
    Stats:
    - Dexterity
Attributes:
  Lethal: true
Category: Special
Damage1: Special
Damage2: ''
Description: The air is so cold it hurts to move, to see, to breath. Escaping should
  be your top priority, for every second you don't your life will be at peril.
Effect: Lethal. All Foes in Range. Reduce the Dexterity of those affected.
Name: Glaciate
Power: 2
Target: All Foes
Type: Ice
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