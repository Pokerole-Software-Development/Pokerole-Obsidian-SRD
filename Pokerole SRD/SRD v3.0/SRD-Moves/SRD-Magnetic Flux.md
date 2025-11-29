---
Accuracy1: Insight
Accuracy2: Channel
AddedEffects:
  StatChanges:
  - Affects: User
    Stages: 1
    Stats:
    - Def
    - SpDef
Attributes: {}
Category: Support
Damage1: ''
Damage2: ''
Description: "The Pok\xE9mon alters the magnetic field around itself to repel damage.\
  \ This also affects other Pok\xE9mon sensible to magnetic charges."
Effect: Target User and Allies in range. Increase by 1 the Defense and Sp. Defense
  of Electric-Type or Steel-Type Targets.
Name: Magnetic Flux
Power: 0
Target: All Allies
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