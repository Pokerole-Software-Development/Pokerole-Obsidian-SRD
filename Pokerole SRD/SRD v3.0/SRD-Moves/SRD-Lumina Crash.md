---
Accuracy1: Insight
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: Targets
    Stages: -2
    Stats:
    - SpDef
Attributes: {}
Category: Special
Damage1: Special
Damage2: ''
Description: "The user flashes a light pattern that crashes the foe\u2019s mind, leaving\
  \ it acting erraticaly for a few moments."
Effect: Single Target. Reduce the Foe's Sp. Defense by 2.
Name: Lumina Crash
Power: 3
Target: Foe
Type: Psychic
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